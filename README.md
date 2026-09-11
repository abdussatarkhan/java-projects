# ShopManagement — Java Desktop POS & Retail Inventory System

<div align="center">

[![Daily Streak](https://img.shields.io/badge/Daily%20Streak-Active%20%F0%9F%94%A5-brightgreen?style=flat-square&logo=github)](https://github.com/abdussatarkhan)
[![Software Portfolio](https://img.shields.io/badge/Portfolio-Software%20Engineering%20%26%20Systems-0e75b6?style=flat-square&logo=github)](https://github.com/abdussatarkhan)
[![Author: Abdussatar](https://img.shields.io/badge/Author-Abdussatar-24292e?style=flat-square&logo=github)](https://github.com/abdussatarkhan)

</div>

[![CI](https://github.com/abdussatarkhan/java-projects/actions/workflows/ci.yml/badge.svg)](https://github.com/abdussatarkhan/java-projects/actions)
[![Java](https://img.shields.io/badge/Java-17+-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://www.oracle.com/java/)
[![GUI](https://img.shields.io/badge/Desktop-Swing_GUI-5382A1?style=for-the-badge&logo=java&logoColor=white)](https://docs.oracle.com/javase/tutorial/uiswing/)
[![Build: Ant](https://img.shields.io/badge/Build-Apache_Ant-A81C7D?style=for-the-badge&logo=apache&logoColor=white)](https://ant.apache.org/)
[![OOP Architecture](https://img.shields.io/badge/Architecture-Clean_OOP-00599C?style=for-the-badge)](https://en.wikipedia.org/wiki/Object-oriented_programming)

> **A modular, object-oriented retail shop management and point-of-sale desktop application engineered in Java with Swing GUI and Apache Ant build automation — featuring product barcode lookup, cashier checkout billing, stock inventory management, and receipt printing.**

---

## 🏛️ System Architecture

```mermaid
graph TD
    UI[Swing Desktop Views & Cashier Dialogs] --> Controller[Shop Controller & Action Listeners]
    Controller --> Service[Billing & Discount Computation Service]
    Controller --> InvManager[Inventory & Stock Management Service]
    InvManager --> Storage[Local File & Database Storage Layer]
    Service --> Receipt[Formatted Printable Receipt Generator]
```

---

## 🌟 Key Features & Capabilities

- **☕ Clean Object-Oriented Architecture**: Modular design leveraging encapsulation, inheritance, polymorphism, and the MVC pattern to separate UI components from business logic.
- **🛒 Cashier Checkout & Billing Engine**: Itemized product catalog lookup, real-time cart subtotal calculation, tax and discount computation, and change due estimation.
- **📦 Inventory Stock Tracking**: Dynamic inventory decrementing upon transaction checkout with automatic low-stock warning thresholds.
- **🧾 Receipt Generation & Output**: Clean formatted receipt generation with itemized invoice lines, timestamped transaction IDs, and store header details.

---

## 🚀 Quickstart & Setup

### Prerequisites
- [Java Development Kit (JDK) 17+](https://www.oracle.com/java/technologies/downloads/)
- [Apache Ant](https://ant.apache.org/) or any modern Java IDE (NetBeans, IntelliJ IDEA, Eclipse)

### 1. Clone the Repository
```bash
git clone https://github.com/abdussatarkhan/java-projects.git
cd java-projects
```

### 2. Build & Run

**Option A: Using Apache Ant**
```bash
cd ShopManagement_v2/ShopManagement
ant compile
ant run
```

**Option B: Using an IDE**
Open the `ShopManagement_v2/ShopManagement` directory in **NetBeans**, **IntelliJ IDEA**, or **Eclipse** as an existing Ant project, resolve project dependencies, and click **Run**.

---

## 🖥️ Application & Operational Interface

<p align="center">
  <img src="screenshots/01_dashboard_preview.png" alt="ShopManagement POS & Retail Inventory Preview" width="95%" />
</p>

> [!TIP]
> You can also open [`dashboard.html`](dashboard.html) directly in any modern browser for an interactive preview of the application management console.

---

## 🗺️ Roadmap & Upcoming Enhancements

- [x] Java OOP architecture with Swing cashier views
- [x] Real-time cart calculation and stock decrementing
- [x] Itemized receipt generation
- [ ] JDBC SQLite local persistence integration
- [ ] ESC/POS thermal USB receipt printer protocol support
- [ ] Barcode USB handheld scanner raw event hook

---

## 👨‍💻 Author & Contact

Built and maintained by **Abdussatar** ([@abdussatarkhan](https://github.com/abdussatarkhan)).  
For technical discussions, collaboration, or queries, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/abdus-satar-5150813b5/) or [GitHub](https://github.com/abdussatarkhan).

---

## 📜 License

This project is licensed under the **MIT License** — see the LICENSE file for details.

---

<div align="center">

### 👨‍💻 Maintained by [Abdussatar (@abdussatarkhan)](https://github.com/abdussatarkhan)
Part of the **[Abdussatar Software Engineering & Systems Portfolio](https://github.com/abdussatarkhan)**.

⭐ If you find this project valuable, consider dropping a star! ⭐

</div>
