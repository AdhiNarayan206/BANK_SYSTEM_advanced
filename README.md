# 🚀 Comet Bank OS v3.0 - Your Financial Universe

A stunning, premium banking system reimagined for the cosmic era. Built with vanilla HTML, CSS, and JavaScript, featuring glassmorphism, AI-driven analytics, and multi-owner account security.

![Comet Bank](https://img.shields.io/badge/Banking-Platform-blueviolet?style=for-the-badge)
![Version](https://img.shields.io/badge/Version-3.0_Pulsar-00f2fe?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)

## ✨ New in v3.0 (The Pulsar Update)

### 📊 Spending Orbit (AI Analytics)
- **Deep Sector Analysis**: Real-time category breakdown of your expenses using **Chart.js**.
- **Stellar Insights**: AI-driven financial advice based on your spending patterns.
- **Visual Constellations**: Interactive doughnut charts showing your financial distribution.

### 🎯 Savings Missions (Joint Goals)
- **Planetary Targets**: Set collaborative savings goals (e.g., "Tesla Planet" or "Lunar Base").
- **Dynamic Progress**: Real-time visual tracking with animated progress bars.
- **Mission Status**: Track missions from initialization to achievement across joint accounts.

### ⚖️ Approval Protocol (Duel-Auth Security)
- **Twin Star Security**: High-value transfers from joint accounts require authorization from the second owner.
- **Authorization Banner**: Real-time pulsing notifications when your verification is required.
- **Secure Processing**: PIN-verified approval/rejection workflow for pending transfers.

### ⚡ Credit Pulsars (Instant Loans)
- **Instant Fuel**: Apply for credit pulsar (loans) directly from the dashboard.
- **Smart Eligibility**: Loan limits calculated based on your monthly average balance.
- **Auto-Repayment**: Integrated repayment tracker and monthly deduction system.

---

## 🎨 Design Highlights
- **Cosmic Background**: Parallax starfield with floating orbital orbs.
- **Glassmorphism UI**: High-blur frosted cards with shimmer effects.
- **Poppins Typography**: Ultra-clean, modern font throughout.
- **Responsive Warp**: Full support for desktop, tablet, and mobile viewing.

---

## 🚀 Quick Start

### 📦 Prerequisites
- **Python 3.10+**
- **MySQL Server**
- **pip** (Python package manager)

### 🛰️ Fast Deployment (One-Command Setup)
We've automated the entire database and feature initialization.

1. **Clone the project** and enter the directory.
2. **Setup Environment**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Configure Database**: Create a `.env` file or update the config in `app.py`.
4. **Initialize Cosmic Features**:
   ```bash
   python setup_comet_bank.py
   ```
   *This script handles tables, seeds cosmic branches, and configures security columns.*

5. **Launch the Core**:
   ```bash
   python app.py
   ```

### 🌍 Accessing the Planet
Simply open `index.html` in your browser. (Using **Live Server** or `npx serve` is recommended for the best experience).

---

## 🔧 API Endpoints (v3.0)

### 👽 Identity & Onboarding
- `POST /api/auth/register` - Synthesize new identity with Branch selection.
- `POST /api/auth/login` - Authenticate and establish JWT uplink.
- `GET /api/branches` - Fetch all active Galactic Sectors.

### 💫 Advanced Banking
- `GET /api/analytics/spending/<acc_id>` - Retrieve spending orbit and AI insights.
- `POST /api/account/missions` - Initialize a new planetary savings goal.
- `GET /api/account/approvals` - List transfers requiring your authorization.
- `POST /api/loans/apply` - Request instant credit fuel.

### 💾 Core Operations
- `POST /api/account/deposit` - Inject credits.
- `POST /api/account/transfer` - Warp credits (requires PIN; triggers Duel-Auth if joint).
- `GET /api/user/dashboard/<user_id>` - Full stellar overview.

---

## 📂 Project Structure

```
BLOOD_BANK_SYSTEM_advanced/
├── index.html           # Single-page Cosmic interface
├── script.js            # Core OS Logic (Auth, Charts, UI)
├── styles.css           # Premium Aesthetics & Animations
├── app.py               # Flask Backend (Hyperdrive)
├── setup_comet_bank.py  # Feature Initialization Script
├── validators.py        # Pydantic Security Schemas
└── requirements.txt     # Dependency warp list
```

---

## 🔐 Security Protocols
- **JWT uplink**: Secure token-based authentication with refresh cycles.
- **PIN Synthesis**: All sensitive maneuvers (Withdrawals, Transfers, Loans) require a 4-6 digit PIN.
- **Encryption**: Passwords and PINs are hashed using PBKDF2.
- **Atomic Operations**: Database transactions ensure no credits are lost in hyperspace.

---

<div align="center">

**Built with 💜 using Comet AI aesthetics and Poppins typography**

🌟 *Your Financial Universe Awaits* 🌟

</div>
