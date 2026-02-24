# 🚀 Comet Bank OS v3.0 - The Financial Universe

**Comet Bank** is a stunning, modern banking system inspired by **Comet AI browser** aesthetics. Built with vanilla HTML, CSS, and JavaScript, it features glassmorphism, cosmic animations, and the elegant **Poppins** font.

The **v3.0 Pulsar Update** transforms the platform into an advanced financial ecosystem with AI-driven analytics, collaborative savings missions, and high-security duel-authentication protocols.

![Comet Bank](https://img.shields.io/badge/Version-3.0_Pulsar-00f2fe?style=for-the-badge)
![Security](https://img.shields.io/badge/Security-Duel--Auth_Enabled-success?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)

---

## ✨ Features

### 🌌 v3.0 Advanced Capabilities (New!)
*   📊 **Spending Orbit (AI Analytics)**: Deep sector breakdown using **Chart.js** with heuristic "Stellar Insights" providing real-time financial advice.
*   🎯 **Savings Missions**: Set collaborative planetary goals (e.g., "Tesla Planet" or "Lunar Base") for joint accounts with live progress tracking.
*   ⚖️ **Approval Protocol**: Duel-Authentication security for high-value transfers from joint accounts, requiring twin-PIN authorization.
*   ⚡ **Credit Pulsars**: Instant 'Credit Fuel' (loans) based on 5x monthly average balance with automated repayment orbits.

### 💼 Core Banking Features
*   ✅ **User Registration**: Complete KYC onboarding with instant account creation and Sector (Branch) selection.
*   📊 **Dashboard**: Real-time account overview with masked IDs and Stellar Standing (Credit Score).
*   💰 **Deposits**: Add funds with automated fraud detection for large transactions.
*   🔄 **Transfers**: Send money between accounts with automatic 1% service fee and secure warp transitions.
*   📋 **Statements**: View transaction history with customizable date ranges (7, 30, 90, or 365 days).
*   📈 **Admin Panel**: Apply system-wide daily interest and view comprehensive audit logs.

### 🎨 Design Highlights
*   **Cosmic Background**: Animated starfield with three-layer parallax and floating gradient orbs.
*   **Glassmorphism UI**: Frosted glass cards with optimized `backdrop-filter: blur(20px)` effects.
*   **Comet AI Theme**: Deep space gradients (Purple, Blue, Cyan, Pink) and Poppins typography.
*   **Smooth Animations**: Floating cards, shimmer effects, and micro-interactions for every state.
*   **Responsive Warp**: Designed to work beautifully on all screen sizes, from mobile to ultra-wide.

---

## 🗄️ Database Architecture (Schema)

| Feature Group | Table | Key Responsibility |
| :--- | :--- | :--- |
| **Identity** | `users`, `auth`, `kyc_documents` | Identity, hashed credentials, and KYC status. |
| **Banking** | `accounts`, `account_members`, `branches` | Financial containers and joint ownership mapping. |
| **Protocols** | `ledger`, `pending_transfers` | Immutable audit trail and Duel-Auth queue. |
| **Goals & Credit**| `savings_missions`, `loans` | Progress tracking and credit pulsar management. |

---

## 🚀 Quick Start

### 📦 Prerequisites
- **Python 3.10+**
- **MySQL Server**
- **Flask** and required dependencies (see `requirements.txt`)

### 🛰️ Setup & Deployment
1.  **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
2.  **Initialize Cosmic Logic**:
    Launch the v3.0 Setup Protocol to create tables, security columns, and seed branches.
    ```bash
    python setup_comet_bank.py
    ```
3.  **Launch the Hyperdrive (Backend)**:
    ```bash
    python app.py
    ```
4.  **Open the Planet (Frontend)**:
    Simply open `index.html` in your browser.

---

## 📱 User Guide

*   **1️⃣ Registration**: Click "Launch Your Journey," select your **Galactic Sector**, and provide KYC details to synthesize your identity.
*   **2️⃣ Dashboard**: Enter your User ID to view your accounts, current Stellar Standing, and Spending Orbit.
*   **3️⃣ Deposits**: Enter Account ID. ⚠️ Deposits over **$10,000** are flagged for review.
*   **4️⃣ Transfers**: Initiate warp transfers. If it's a joint account, a **Pending Authorization** banner will appear for your partner.
*   **5️⃣ Savings Missions**: Initialize as a team. Use 'Twin Star' accounts to reach planetary goals faster.
*   **6️⃣ Admin Access**: Scale the system by applying daily interest or auditing the terminal logs.

---

## 🎨 Design System

### **Color Palette**
```css
Primary Purple: #667eea
Secondary Violet: #764ba2
Primary Blue: #4facfe
Accent Cyan: #00f2fe
Primary Pink: #f093fb

Dark Background: #0a0e27
Darker Background: #050816
```

### **Special Effects**
- ⭐ **Starfield**: Three-layer parallax stars.
- 🌌 **Floating Orbs**: Gradient orbs with blur filters.
- 💫 **Shimmer Text**: Animated gradient headings.
- 🎴 **Floating Cards**: 3D hover effects with glow.

---

## 🔐 Security & Optimization

*   **Identity Uplink**: JWT-based session management with secure refresh cycles.
*   **PIN Protocol**: All sensitive maneuvers require a 4-6 digit Transaction PIN.
*   **Fraud Detection**: Automated flagging of high-value deposits ($10k+).
*   **Data Masking**: Account IDs are truncated (e.g., `abcd****xyz1`) for privacy.
*   **Performance**: All animations use GPU-accelerated CSS transforms for buttery-smooth interactivity.

---

## 🚀 Future Enhancements

- [ ] Mobile menu implementation.
- [ ] Real-time balance updates (WebSockets).
- [ ] Transaction notifications.
- [ ] Export statements to PDF.
- [ ] Currency conversion.
- [ ] Dark/Light mode toggle.

---

<div align="center">

**Built with 💜 using Comet AI aesthetics and Poppins typography**

🌟 *Your Financial Universe Awaits* 🌟

</div>
