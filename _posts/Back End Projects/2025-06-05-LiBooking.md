---
title: LiBooking
classes: wide
header:
  teaser: https://raw.githubusercontent.com/AbdoOo20/Images/refs/heads/main/LiBooking/liLogo.png
ribbon: MidnightBlue
categories:
  - Back_End_Projects
toc: true
---

# 🏨 LiBooking

LiBooking is an all-in-one Hospitality & Event Management Ecosystem designed to revolutionize the booking industry in Libya. By bridging the gap between cloud-based reservations and on-ground POS operations, it offers a unified platform for managing hotels, luxury chalets, and event venues with real-time facility synchronization and a secure local financial layer.

---

## Core Business Logic

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

## Architectural Excellence

The project follows a rigorous **Clean Architecture (Onion Architecture)** to ensure complete separation of concerns and maintainability:

* **Onion Architecture:** Decoupling the core business logic from external concerns (UI, DB, Frameworks).
* **Unit of Work Pattern:** Ensuring data integrity by grouping multiple repository operations into a single transaction.
* **Specification Design Pattern:** Encapsulating complex query logic into reusable, testable business rules.
* **Repository Pattern:** Abstracting data access for cleaner, more maintainable code.

---

## Technical Features

- **Push Notifications:** Real-time alerts and booking confirmations via **Firebase (FCM)**.
- **Global Pricing Engine:** Automatic price calculation based on user-specific currency settings.
- **Real-time Sync:** Webhook and API-based integration with local POS systems.
- **Dynamic Services:** Flexible metadata system to manage different services for each property type.

---

## Technology Stack

- **Backend:** .NET 8 / .NET Core Web API
- **Database:** Microsoft SQL Server
- **Architecture:** Onion Architecture + DDD Principles
- **Patterns:** Unit of Work, Specification Pattern, Repository Pattern
- **Real-time:** Firebase Cloud Messaging (FCM)
- **Security:** JWT Authentication & Role-Based Authorization

---

## 📱 Application & Live Demo

Experience the ecosystem across different platforms:

| Platform | Link |
| :--- | :--- |
| **Website** | [Visit Website](https://libooking.com/) |
| **Android App** | [Download from Play Store](https://play.google.com/store/apps/details?id=com.libooking.app) |
| **IOS App** | [Download from App Store](https://apps.apple.com/eg/app/libooking/id6754592394)

---

### Test Credentials

To explore the system features, you can use these demo accounts:

* **User Account:** `+201018754602` / `Abdo@123`

---

## Code

[URL](https://github.com/mmtechLy4/libooking_backend)

---

