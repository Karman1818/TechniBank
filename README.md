# 🏦 TechniBank — Online Banking & Financial Dashboard

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

**TechniBank** is a modern, responsive web application simulating an online banking platform. Built with clean HTML5 semantic structure, modular CSS3 styling, and interactive JavaScript components, TechniBank offers a comprehensive suite of digital banking utilities ranging from account management and wire transfers to real-time cryptocurrency trading calculations and financial billing metrics.

---

## 🌟 Key Features

### 1. 🏠 Main Dashboard (`index.html`)
* **Intuitive Header Navigation:** Global search bar, notifications modal trigger, message contact modal, user profile link, and session logout button.
* **Banking Services Overview:** Quick navigation shortcuts to payment handling, billing histories, and investment portals.
* **Card Showcase:** Visual gallery presenting available debit and credit card products offered by TechniBank.
* **Interactive Notification Center:** Real-time modal popups tracking security events (device logins, ATM cash operations, transfers, crypto purchases, system maintenance alerts).

### 2. 💳 Payment Hub & Wire Transfers (`Platnosci.html`)
* **Saved Beneficiaries Directory:** List of saved contact recipients with IBAN formatted account numbers and quick removal options.
* **Flexible Transfer Types:** Support for domestic bank transfers, self-account transfers, and mobile phone top-ups.
* **Payment Form Interface:** User-friendly form inputs for fast, reliable transaction simulation.

### 3. 📊 Billing & Payment History (`biling.html`)
* **Financial Overview Widgets:** At-a-glance metrics for monthly expenses, upcoming scheduled payments, and recent transaction timestamps.
* **Payment Methods Management:** Overview of registered payment vehicles (Visa, MasterCard, Debit Cards) with options to add new methods.
* **Transaction History Table:** Detailed breakdown log featuring Transaction IDs, dates, and currency values.

### 4. 📈 Investment & Cryptocurrency Terminal (`inwestuj.html`, `kryptowaluty.html`)
* **Multi-Asset Investment Hub:** Portal to access cryptocurrency trading, government bonds, and stock market investments.
* **Live Crypto Calculator:** Interactive calculator for popular cryptocurrencies (Bitcoin `BTC`, Binance Coin `BNB`, Ethereum `ETH`), calculating live purchase totals based on user quantity input.

### 5. 👤 Account & Profile Settings (`profile.html`)
* **Profile Customization:** Profile avatar image update section supporting standard image formats (JPG, PNG).
* **Personal Data Management:** Updateable inputs for username, first and last name, PESEL identification number, geographical location, and email address.
* **Account Control:** Integrated security settings and credential management.

### 6. 🔐 Authentication Flow (`logowanie.html`, `rejestracja.html`)
* Dedicated login and registration screens providing a complete user onboarding flow.

---

## 📂 Project Architecture

```
TechniBank/
├── css/                     # Stylesheets and visual assets
│   ├── img/                 # Application graphics, icons, and media files
│   ├── Platnosci.css        # Styles for payments and transfer forms
│   ├── autorization.css     # Authentication page styling
│   ├── bell.css             # Notification modal styles
│   ├── biling.css           # Billing metrics and transaction table styles
│   ├── inwestuj.css         # Investment hub portal styles
│   ├── kryptowaluty.css     # Cryptocurrency exchange terminal styles
│   ├── mail.css             # Contact modal styles
│   ├── profile.css          # User profile settings styles
│   ├── style.css            # Core global stylesheet
│   └── style1.css           # Main dashboard layout styles
├── javascript/              # Client-side JavaScript files
│   ├── bell.js              # Notification modal interaction logic
│   └── mail.js              # Contact modal popup logic
├── index.html               # Main Dashboard page
├── Platnosci.html           # Payments & Wire Transfers page
├── biling.html              # Billing & Payment History page
├── inwestuj.html            # Investment Hub landing page
├── kryptowaluty.html        # Cryptocurrency Market page
├── logowanie.html           # User Login page
├── rejestracja.html         # User Registration page
├── profile.html             # Account Profile page
└── README.md                # Project documentation
```

---

## 🛠️ Technology Stack

* **Structure:** HTML5
* **Styling:** CSS3 (Flexbox, CSS Grid, Custom Popups, Responsive Layouts)
* **Logic & Interactivity:** Vanilla JavaScript (DOM Manipulation, Dynamic Value Calculations, Modal Dialogs)
* **Typography:** Google Fonts (*Roboto*, *Comic Neue*, *Bungee Spice*)

---

## 🚀 Getting Started

Because **TechniBank** is built with standard web technologies, running it requires no dependencies or build tools!

### Prerequisites
* Any modern web browser (e.g., Google Chrome, Mozilla Firefox, Microsoft Edge, Safari).

### Quick Start
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Karman1818/TechniBank.git
   ```
2. **Navigate into the project directory:**
   ```bash
   cd TechniBank
   ```
3. **Launch the application:**
   * Open `index.html` directly in your browser or launch it using a local development server such as VS Code's **Live Server** extension.

---

## 👥 Authors

* **Marceli Karman** — [GitHub Profile](https://github.com/Karman1818)
* **Adam Pukaluk**

---

## 📜 License

This project is open-source and available for educational and portfolio demonstration purposes.
