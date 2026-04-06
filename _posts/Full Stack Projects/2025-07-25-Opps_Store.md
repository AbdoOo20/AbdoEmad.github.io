---
title: Opps Store
classes: wide
header:
  teaser: https://raw.githubusercontent.com/AbdoOo20/Images/refs/heads/main/OppsStore/newlogo1.png
ribbon: DarkOrange
categories:
  - Full_Stack_Projects
toc: true
---

# 📱 Opps Store - Egypt's Premier Mobile Marketplace

**Oppos Store** is a specialized multi-vendor e-commerce platform designed to unify mobile retailers across Egypt. The platform allows mobile shop owners to act as vendors, showcasing their products and services to a nationwide audience. From the latest flagship devices to professional maintenance services, Oppos Store is the digital hub for everything mobile.

---

## Core Categories

The platform is meticulously organized into four primary pillars:
1. **New Phones:** Featuring the latest releases from global brands with official warranties.
2. **Used Phones:** A trusted marketplace for pre-owned devices with graded condition reports.
3. **Accessories:** A vast collection of chargers, cases, screen protectors, and wearables.
4. **Maintenance Services:** A dedicated section for booking repairs and connecting with certified technicians.

---

## Key Features

### Vendor Ecosystem (Multi-Vendor)
* **Merchant Dashboards:** Each shop gets a dedicated panel to manage inventory, track sales, and process orders.
* **Store Profiles:** Vendors can customize their digital storefront to build brand loyalty.
* **Inventory Management:** Real-time tracking of stock levels across different mobile models and colors.

### Customer Experience
* **Seamless Shopping:** Advanced filtering by brand, price, condition (New/Used), and specs.
* **Secure Checkout:** Integrated shopping cart with multiple payment options.
* **Order Tracking:** Customers can monitor their order status from "Pending" to "Delivered."

### Service Booking
* **Maintenance Portal:** Users can describe their device issues and book a repair slot with top-rated local shops.

### Advanced Admin Control Panel
* **Vendor Approval:** Admins verify and approve new merchants to ensure marketplace quality.
* **Commission Management:** Automated calculation of platform fees per sale.
* **Global Analytics:** Comprehensive sales reports to monitor market trends in Egypt.

---

## Technology Stack

- **Backend:** ASP.NET MVC (C#)
- **Database:** Microsoft SQL Server
- **Architecture:** **Database First Approach**
- **Data Access:** Entity Framework & **Stored Procedures (SPs)** for optimized performance and complex logic execution.
- **Frontend:** Bootstrap 5, jQuery, DataTables.net
- **Security:** ASP.NET Identity for role-based access (Admin, Vendor, Customer)

---

## Database Architecture & Logic
The system utilizes a robust SQL schema designed for high performance and scalability:
* **Database First:** The project structure was built upon an existing, optimized SQL schema.
* **Stored Procedures:** All critical operations (Complex Filtering, Order Processing, and Vendor Analytics) are handled via **Stored Procedures** called directly from C# for maximum efficiency.
* **Products Table:** Supports polymorphic relations for New vs. Used items.
* **Orders & OrderItems:** For detailed transaction logging.
* **Vendor Ratings:** A feedback loop system to maintain store quality.

---

## Code

[URL](https://github.com/AbdoOo20/OppsStore)

---

## Project Preview

<table>
  <tr>
    <td><img src="https://raw.githubusercontent.com/AbdoOo20/Images/refs/heads/main/OppsStore/0.png"/></td>
    <td><img src="https://raw.githubusercontent.com/AbdoOo20/Images/refs/heads/main/OppsStore/1.png"/></td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/AbdoOo20/Images/refs/heads/main/OppsStore/2.png"/></td>
    <td><img src="https://raw.githubusercontent.com/AbdoOo20/Images/refs/heads/main/OppsStore/3.png"/></td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/AbdoOo20/Images/refs/heads/main/OppsStore/4.png"/></td>
    <td><img src="https://raw.githubusercontent.com/AbdoOo20/Images/refs/heads/main/OppsStore/5.png"/></td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/AbdoOo20/Images/refs/heads/main/OppsStore/6.png"/></td>
    <td><img src="https://raw.githubusercontent.com/AbdoOo20/Images/refs/heads/main/OppsStore/7.png"/></td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/AbdoOo20/Images/refs/heads/main/OppsStore/8.png"/></td>
    <td><img src="https://raw.githubusercontent.com/AbdoOo20/Images/refs/heads/main/OppsStore/9.png"/></td>
  </tr>
</table>
