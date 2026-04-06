---
title: Libya Booking & POS Integrated System
classes: wide
header:
  teaser: https://raw.githubusercontent.com/AbdoOo20/Images/refs/heads/main/projects/booking-teaser.png
ribbon: MidnightBlue
categories:
  - Backend_Development
  - DotNet_Core_WebAPI
toc: true
---

# 🏨 Integrated Hospitality & Event Management System (Libya)

A high-performance, scalable Backend solution built to manage Hotels, Chalets, and Event Halls across Libya. This system is uniquely integrated with a **POS (Point of Sale)** system for real-time facility control and supports a complete financial ecosystem including E-Wallets and multiple Payment Gateways.

---

## 🌟 Core Business Logic

### 1. Accommodations (Stay Management)
- **Granular Booking:** Supports booking by **Individual Rooms** (Hotels) or **Full Units** (Apartments, Chalets, and Villas).
- **Service Showcasing:** Each accommodation displays a dynamic list of available services and amenities.

### 2. Event Halls (Venue Management)
- **Shift-Based Booking:** Specialized logic for **Morning** and **Evening** shifts.
- **Facility Control:** Real-time synchronization with the physical venue via **POS Integration**.

### 3. Financial & Payment Engine
- **Multi-Currency System:** Prices are dynamically converted and displayed based on the **User's Local Currency**.
- **E-Wallet:** Integrated digital wallet for seamless payments and refunds.
- **Payment Gateways:** Support for major local and international payment providers.

---

## 🏗️ Architectural Excellence

The project follows a rigorous **Clean Architecture (Onion Architecture)** to ensure complete separation of concerns and maintainability:

* **Onion Architecture:** Decoupling the core business logic from external concerns (UI, DB, Frameworks).
* **Unit of Work Pattern:** Ensuring data integrity by grouping multiple repository operations into a single transaction.
* **Specification Design Pattern:** Encapsulating complex query logic into reusable, testable business rules.
* **Repository Pattern:** Abstracting data access for cleaner, more maintainable code.

---

## 🚀 Technical Features

- **Push Notifications:** Real-time alerts and booking confirmations via **Firebase (FCM)**.
- **Global Pricing Engine:** Automatic price calculation based on user-specific currency settings.
- **Real-time Sync:** Webhook and API-based integration with local POS systems.
- **Dynamic Services:** Flexible metadata system to manage different services for each property type.

---

## 🛠️ Technology Stack

- **Backend:** .NET 8 / .NET Core Web API
- **Database:** Microsoft SQL Server
- **Architecture:** Onion Architecture + DDD Principles
- **Patterns:** Unit of Work, Specification Pattern, Repository Pattern
- **Real-time:** Firebase Cloud Messaging (FCM)
- **Security:** JWT Authentication & Role-Based Authorization

---

## 💻 Code & Documentation

[URL](https://github.com/AbdoOo20/Libya-Booking-System)

---

## ⚙️ Key Technical Implementations

> **Note on Performance:** The system uses the **Specification Pattern** to handle complex filtering of rooms and halls (by date, shift, currency, and amenities) without cluttering the Service Layer.

```csharp
// Example of the Specification Pattern used in the project
var spec = new RoomWithCurrencySpecification(userCurrencyId, roomType);
var room = await _unitOfWork.Repository<Room>().GetEntityWithSpec(spec);
