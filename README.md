<div align="center">

# 🍽️ RestroQT

**The Operating System for Modern Hotels & Restaurants**

<br>

[![Status](https://img.shields.io/badge/status-active-brightgreen)]()
[![Platform](https://img.shields.io/badge/platform-Web%20%7C%20Mobile-blue)]()
[![License](https://img.shields.io/badge/license-Proprietary-purple)]()
[![Demo](https://img.shields.io/badge/demo-request-ff6b6b)]()

<br>

<img src="assets/screenshots/hero-dashboard.jpg" alt="RestroQT Dashboard" width="90%" style="border-radius: 12px; box-shadow: 0 8px 32px rgba(0,0,0,0.15);">

*Your entire property at a glance — live room grid, active guests, and order statuses.*

</div>

---

## 🚀 What is RestroQT?

RestroQT is a **real-time hospitality operating system** that connects every part of your hotel or restaurant into one live dashboard — rooms, orders, kitchen, billing, cash, and guests.

```
Guest orders food
    ↓
Kitchen sees it instantly
    ↓
Chef updates status
    ↓
Reception & guest see it live
    ↓
Bill generated → Cash received → Ledger updated
```

> **Everything live. Everything synced. One system.**

---

## 🖥️ Product Experience

### Live Dashboard

The command center. See every room, every active guest, every live order — all on one screen.

<img src="assets/screenshots/hero-dashboard.jpg" alt="Live Dashboard" width="90%" style="border-radius: 8px;">

---

### Order Management

Quick Ticket (QT) ordering for rooms & tables. Full order lifecycle: `OPEN → PREPARING → SERVED → BILLED`. Cancellations, modifications, and multi-language support included.

<img src="assets/screenshots/hero-orders.jpg" alt="Order Management" width="90%" style="border-radius: 8px;">

---

### Smart Billing Engine

GST/Non-GST billing, instant PDF invoices, discount support, bill history, email delivery, and bill editing *(PRO)*.

<img src="assets/screenshots/hero-billing.jpg" alt="Billing Engine" width="90%" style="border-radius: 8px;">

---

### Analytics & Reports

Real-time revenue tracking, order flow insights, occupancy visibility, and cash flow monitoring with CSV export *(PRO)*.

<img src="assets/screenshots/hero-analytics.jpg" alt="Analytics" width="90%" style="border-radius: 8px;">

---

### 👨‍🍳 Kitchen Display System

Real-time order feed with color-coded statuses, sound alerts, one-tap updates, modification queue, and emergency mode.

<img src="assets/screenshots/kitchen-orders.png" alt="Kitchen Orders" width="45%" style="border-radius: 8px; display: inline-block;">
<img src="assets/screenshots/kitchen-detail.png" alt="Kitchen Detail" width="45%" style="border-radius: 8px; display: inline-block;">

*Left: Live order feed &nbsp;|&nbsp; Right: Order detail view*

<img src="assets/screenshots/kitchen-overview.png" alt="Kitchen Overview" width="90%" style="border-radius: 8px;">

---

### 🖥️ Reception & Front Desk

Check-in guests, create orders, generate bills, manage walk-ins, and handle cash — all from one place.

<img src="assets/screenshots/reception-dashboard.jpg" alt="Reception Dashboard" width="45%" style="border-radius: 8px; display: inline-block;">
<img src="assets/screenshots/reception-checkin.jpg" alt="Guest Check-in" width="45%" style="border-radius: 8px; display: inline-block;">

*Left: Reception dashboard &nbsp;|&nbsp; Right: Guest check-in*

<img src="assets/screenshots/reception-guest.jpg" alt="Guest Management" width="45%" style="border-radius: 8px; display: inline-block;">
<img src="assets/screenshots/reception-menu.jpg" alt="Food Menu" width="45%" style="border-radius: 8px; display: inline-block;">

*Left: Guest management &nbsp;|&nbsp; Right: Food menu & ordering*

---

## 🔥 Core Features

### 🖥️ Live Dashboard
| Feature | Description |
|---------|-------------|
| Room Occupancy Grid | See every room — green for occupied, available for vacant |
| Active Guest Tracking | Guest names, amounts due, order statuses |
| Live Order Monitoring | Every active order with real-time status |
| Walk-in Order Alerts | Automatic 3-minute elapsed timer with notification |
| Auto-Refresh | 10-second polling keeps data fresh |

### 🍽️ Order Management
- **Quick Ticket (QT)** ordering for rooms & tables
- **Kitchen Order Tickets (KOT)** auto-generated per order
- **Order Lifecycle:** `OPEN → PREPARING → SERVED → BILLED`
- **Cancellation** with reason tracking
- **Modification tracking** with chef approval workflow
- **Multi-language** support (English + Hindi)

### 👨‍🍳 Kitchen Display System
- **Real-time order feed** — new orders appear instantly
- **Color-coded statuses** — blue (new), amber (preparing), green (served)
- **Sound alerts** — distinct audio for new orders & modifications
- **One-tap status updates** — chefs tap to progress orders
- **Modification queue** — review & accept/reject changes
- **Emergency mode** — one-click kitchen close during rush

### 🧾 Smart Billing Engine
| Feature | Details |
|---------|---------|
| GST / Non-GST Billing | Choose per bill, configurable rates |
| Instant Invoice Generation | One click from selected orders |
| PDF Download | Professional-grade bill PDFs with logo |
| Discount Support | Percentage or fixed amount with reason |
| Bill History | Full search, filter, and export |
| Email Bills | Send directly to guests via SMTP |
| Bill Editing | Add items, apply discounts *(PRO)* |

### 💰 Cash & Shift Management
| Feature | Description |
|---------|-------------|
| Shift-Based Tracking | Open/close shifts with opening balance |
| Cash In / Cash Out | Record every rupee with accountability |
| Staff Accountability | Know who received what |
| Tamper-Proof Ledger | Hash-chained transactions |
| Handover System | Seamless shift handover between receptionists |

### 📊 Real-Time Analytics
- Revenue tracking with monthly breakdowns
- Order flow insights (Room vs Walk-in)
- Occupancy visibility
- Cash flow monitoring
- CSV export for accounting *(PRO)*

---

## 🏨 Built For

| Type | Perfect For |
|------|-------------|
| 🏨 **Hotels** | Multi-room properties of any size |
| 🏖️ **Resorts** | Properties with diverse dining & services |
| 🍽️ **Restaurants** | Standalone dining establishments |
| ☕ **Cafés** | Quick-service coffee & food |
| 🏪 **Quick Service Outlets** | Fast-paced food service |

---

## 👥 Role-Based Access

| Role | Access Level |
|------|-------------|
| 👑 **Owner** | Full control — financials, settings, everything |
| ⚙️ **Admin** | Operations + user management |
| 🖥️ **Reception** | Front desk — orders, billing, cash, guests |
| 👨‍🍳 **Kitchen** | Order execution only |

---

## 🔐 Security & Architecture

| Feature | Detail |
|---------|--------|
| 🔒 **Tenant Isolation** | Every property's data completely separated |
| 🔑 **JWT Authentication** | Secure token-based login with auto-refresh |
| 👤 **Role-Based Permissions** | 4-tier access control |
| 💾 **Encrypted Backups** | Fernet encryption with cloud storage |
| 📋 **Audit-Ready Logs** | Every change tracked with who & when |

Real-time updates via **WebSocket / MQTT**:

```
Order Placed → MQTT Message → Kitchen Display (0.5s)
Status Update → MQTT Message → Dashboard + Guest (0.5s)
```

---

## 📞 Get In Touch

> Want a live demo? We'd love to show you what RestroQT can do.

| Method | Details |
|--------|---------|
| 🐛 **GitHub Issues** | Open an issue for questions or feature requests |
| 📧 **Email** | *(add your email here)* |
| 💬 **WhatsApp** | *(add your WhatsApp link here)* |

---

<br>

<div align="center">

## ⭐ RestroQT

*Not just a POS system — a complete hospitality operating system.*

<br>

**Made with ❤️ for hotels and restaurants everywhere**

</div>
