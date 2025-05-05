# 🏨 Hotel Management System

A comprehensive **Hotel Management System** built using **Java Swing (JFrame)** for the user interface and **JDBC** for database connectivity. This desktop application simulates hotel operations like room bookings, employee management, check-in/check-out, and customer tracking.

---

## 🚀 Features

- 🧾 Add & manage customers, employees, and drivers
- 🏢 Room management (add, update, view)
- 🔑 Hotel reception dashboard
- 📥 Check-in / Check-out system
- 🔍 Room search and pickup service
- 👤 Admin login and role-based dashboard
- 🗃 Departmental and employee info views

---

## 🛠 Technologies Used

- Java (JDK 8 or above)
- Swing (JFrame-based GUI)
- JDBC (Java Database Connectivity)
- MySQL or compatible RDBMS

---

## 📦 Class Structure

| Class Name            | Purpose                                              |
|-----------------------|------------------------------------------------------|
| `HotelManagementSystem` | Main entry point with launcher frame                |
| `Login`               | Authentication screen for admin access               |
| `Dashboard`           | Central hub for all hotel management modules         |
| `AddEmployee` / `AddEmployees` | Forms to add new employees                        |
| `AddRoom`             | Interface to create new room records                 |
| `AddDrivers`          | Add and manage hotel transport staff                 |
| `NewCustomer`         | Check-in form to register new guests                 |
| `Checkout`            | Process guest check-out and generate invoice         |
| `CustomerInfo`        | View all customer-related information                |
| `Room`, `SearchRoom`  | Browse and filter available/occupied rooms           |
| `Reception`           | Acts as the receptionist’s control center            |
| `Pickup`              | Assign vehicles for airport/train station pickups    |
| `Department`, `Employee`, `ManageInfo` | Administer internal departments and staff |
| `UpdateRoom`, `UpdateCheck` | Modify room/customer status or booking info    |
| `Conn`                | Centralized JDBC connection handler                  |

---

