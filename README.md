# 🚀 Comet Bank OS v3.0 - The Financial Universe

**Comet Bank OS v3.0** is a premium, full-stack banking simulation designed with a "Cosmic" aesthetic. Moving beyond simple ledger tracking, v3.0 introduces AI-driven spending analytics, collaborative savings missions, and a high-security Duel-Authentication protocol for joint accounts.

![Comet Bank](https://img.shields.io/badge/Version-3.0_Pulsar-00f2fe?style=for-the-badge)
![Status](https://img.shields.io/badge/Security-Duel--Auth_Enabled-success?style=for-the-badge)
![Database](https://img.shields.io/badge/DB-MySQL-blue?style=for-the-badge)

---

## 🌌 Core Philosophy & Features

### 1. 📊 Spending Orbit (AI-Powered Analytics)
Understanding your wealth is the first step to growing it. v3.0 features a real-time spending radar.
- **Deep Sector Breakdown**: Uses **Chart.js** to categorize every transaction into "orbits" (Shopping, Food, Fuel, etc.).
- **Stellar Insights**: A heuristic engine that analyzes your average balance vs. monthly burn rate to provide "AI Insights" or warnings if a sector is consuming too much fuel.

### 2. 🎯 Savings Missions (Shared Goals)
Banking is better together. v3.0 introduces collaborative goals for "Twin Star" (Joint) accounts.
- **Goal Initialization**: Set a target amount and a cosmic mission name (e.g., "Solar Cruiser Deposit").
- **Live Progress Tracking**: Visual progress bars that update in real-time as you and your partner deposit funds.
- **Milestone Rewards**: Tracking from 'Active' to 'Accomplished' status.

### 3. ⚖️ Approval Protocol (Duel-Auth Transfer)
Security in the cosmic era requires more than just a password.
- **High-Value Guard**: Transfers exceeding a specific threshold from a joint account are placed in "Pending" status.
- **Authorization Uplink**: The second owner receives a pulsing alert on their dashboard and must provide their secure PIN to approve the transfer.
- **Immutable Ledger**: Transactions move to the ledger only after twin-authorization is achieved.

### 4. ⚡ Credit Pulsars (Smart Loans)
Instant credit fuel for your journey, governed by your Stellar Standing.
- **Calculated Eligibility**: Loan capacity is dynamically calculated based on 5x your monthly average balance.
- **Stellar Standing**: A credit scoring system starting at 750 points, which fluctuates based on repayment behavior.
- **Auto-Repayment Orbit**: Automated monthly deductions from your funding account.

### 5. 🎨 Cosmic Design System
- **Glassmorphism**: High-fidelity frosted glass components with optimized backdrop-blur filters.
- **Parallax Starfield**: Multiple layers of depth for a truly immersive experience.
- **Micro-Animations**: Shimmer effects on buttons, pulsing hazard banners, and floating card interactions.

---

## �️ Database Architecture (Schema)

The system runs on an interconnected MySQL relational model designed for high traceability.

### � User & Auth Core
| Table | Description | Key Columns |
| :--- | :--- | :--- |
| `users` | Core identity & scoring | `user_id`, `full_name`, `email`, `stellar_standing` |
| `auth` | Secure credentials | `user_id`, `password_hash` (PBKDF2) |
| `kyc_documents` | Identity verification | `user_id`, `doc_type`, `doc_num`, `verification_status` |

### 💳 Account Engine
| Table | Description | Key Columns |
| :--- | :--- | :--- |
| `accounts` | Financial containers | `account_id`, `account_type`, `balance`, `pin_hash`, `branch_id` |
| `account_members` | Joint ownership map | `account_id`, `user_id`, `role` (Owner/Joint) |
| `branches` | Galactic sectors | `branch_id`, `branch_name`, `location`, `manager_name` |

### 🔄 Ledger & Protocol
| Table | Description | Key Columns |
| :--- | :--- | :--- |
| `ledger` | Immutable transaction logs | `transaction_id`, `account_id`, `amount`, `initiated_by`, `status` |
| `pending_transfers` | Duel-Auth queue | `transfer_id`, `account_id`, `amount`, `beneficiary`, `status` |
| `savings_missions` | Progress tracking | `mission_id`, `account_id`, `target_amount`, `current_progress` |

### ⚡ Lending & Audit
| Table | Description | Key Columns |
| :--- | :--- | :--- |
| `loans` | Credit pulsar data | `loan_id`, `account_id`, `principal`, `monthly_repayment`, `next_date` |
| `audit_log` | Security audit trail | `log_id`, `table_name`, `action_type`, `old_value`, `new_value` |

---

## 🛠️ Technical Stack

### **Frontend (The Interface)**
- **Vanilla JS (ES6+)**: Custom `AuthManager` class for JWT handling and fetch interceptors.
- **CSS3 Power**: Custom variables (`:root`) used for the entire thematic color palette.
- **Chart.js**: Dynamic data visualization for spending orbits.
- **Glassmorphism**: High-performance blur effect (Backdrop-filter).

### **Backend (The Navigator)**
- **Flask (Python)**: RESTful API architecture.
- **Flask-JWT-Extended**: Secure token-based session management.
- **Pydantic**: Robust data validation for every incoming request.
- **MySQLdb**: High-performance database connectivity.

---

## � Setup & Initialization

### 1. Galactic Installation
```bash
# Install dependencies
pip install -r requirements.txt
```

### 2. Hyperdrive Initialization
Before launching the server, you must initialize the cosmic tables and seed the galactic sectors.
```bash
# Runs the v3.0 Setup Protocol
python setup_comet_bank.py
```
*What this does:*
1. Creates all missing tables (Missions, Loans, Approvals).
2. Adds the `pin_hash` and `stellar_standing` security columns.
3. Seeds initial branches like *Sirius Prime* and *Andromeda Hub*.

### 3. Launching the Core
```bash
python app.py
```

---

## 🔐 Security Protocols
- **Atomic Operations**: All financial updates use database transactions. If any part of a transfer fails, the entire operation is rolled back to prevent credit loss.
- **Data Masking**: Account IDs are truncated (`****`) in the UI to prevent shoulder-surfing.
- **JWT Lifecycles**: Access tokens expire every hour, with a refresh token workflow to maintain the uplink securely.

---

<div align="center">

**Built with 💜 by the Comet Banking Team**

🌟 *Your Financial Universe Awaits* 🌟

</div>
