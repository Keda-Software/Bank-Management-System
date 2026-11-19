# 🏦 Bank Management System

A responsive web-based Bank Management System built with HTML, CSS, and JavaScript. The application provides an interactive banking dashboard for managing customer accounts, tracking balances, and performing banking transactions such as deposits, withdrawals, and transfers.

## 📌 Project Overview

The Bank Management System is a frontend web application designed to simulate basic banking operations. It allows an administrator to create and manage bank accounts, view account balances, record transactions, and monitor banking activities through a dashboard.

The application uses browser LocalStorage to save account and transaction data, allowing information to remain available after refreshing the browser.

## ✨ Features

- **Admin Login:** Login interface for accessing the banking dashboard.
- **Dashboard:** Displays total accounts, total balance, deposits, and withdrawals.
- **Account Management:** Create, view, search, filter, and delete bank accounts.
- **Deposit Management:** Deposit money into customer accounts.
- **Withdrawal Management:** Withdraw money from accounts with balance validation.
- **Money Transfers:** Transfer money between existing accounts.
- **Transaction History:** View and track recorded financial transactions.
- **Transaction Search and Filtering:** Find transactions and filter transaction records.
- **Account Validation:** Prevent invalid operations and account-related errors.
- **Persistent Data:** Uses LocalStorage to store account and transaction records.
- **Dark Mode:** Switch between light and dark themes.
- **Responsive Design:** Works on desktop, tablet, and mobile screens.

## ⚙️ Functional Requirements

### 1. Authentication

- The system shall provide an administrator login interface.
- The administrator shall enter a username and password to access the dashboard.
- The system shall validate login credentials.
- The system shall display an error message when invalid credentials are entered.
- The system shall allow authorized demo access to the banking dashboard.

**Demo Credentials:**
- Username: `admin`
- Password: `1234`

### 2. Dashboard Management

- The system shall display the total number of bank accounts.
- The system shall display the total balance across all accounts.
- The system shall display the total deposit amount.
- The system shall display the total withdrawal amount.
- The system shall update dashboard statistics when banking data changes.
- The dashboard shall provide navigation to different banking sections.

### 3. Account Management

- The system shall allow the administrator to create new bank accounts.
- The system shall store account information.
- The system shall display registered accounts.
- The system shall allow searching for accounts.
- The system shall allow filtering accounts where supported.
- The system shall allow the administrator to delete eligible accounts.
- The system shall prevent deletion of accounts with a non-zero balance.
- The system shall update account information displayed on the dashboard when account data changes.

### 4. Deposit Management

- The system shall allow the administrator to select an account for depositing money.
- The system shall allow the administrator to enter a deposit amount.
- The system shall validate the deposit amount.
- The system shall update the selected account's balance after a successful deposit.
- The system shall record the deposit in transaction history.
- The system shall update dashboard statistics after a successful deposit.

### 5. Withdrawal Management

- The system shall allow the administrator to select an account for withdrawing money.
- The system shall allow the administrator to enter a withdrawal amount.
- The system shall validate the withdrawal amount.
- The system shall prevent withdrawals exceeding the available account balance.
- The system shall update the account balance after a successful withdrawal.
- The system shall record the withdrawal in transaction history.
- The system shall update dashboard statistics after a successful withdrawal.

### 6. Money Transfer Management

- The system shall allow the administrator to select a source account.
- The system shall allow the administrator to select a destination account.
- The system shall allow the administrator to enter a transfer amount.
- The system shall validate the source and destination accounts.
- The system shall prevent transfers between the same account where validation is implemented.
- The system shall prevent transfers exceeding the source account's available balance.
- The system shall deduct the transfer amount from the source account.
- The system shall add the transfer amount to the destination account.
- The system shall record the transfer in transaction history.
- The system shall update account balances and dashboard statistics after a successful transfer.

### 7. Transaction Management

- The system shall record successful deposits.
- The system shall record successful withdrawals.
- The system shall record successful transfers.
- The system shall display transaction records.
- The system shall allow searching transaction records.
- The system shall allow filtering transaction records.
- The system shall maintain transaction records in LocalStorage.
- The system shall provide transaction information for tracking account activities.

### 8. Data Storage

- The system shall store account information in browser LocalStorage.
- The system shall store transaction history in browser LocalStorage.
- The system shall retrieve stored information when the application loads.
- The system shall preserve saved data after browser refreshes, provided LocalStorage is not cleared.
- The system shall update stored data after successful banking operations.

### 9. User Interface

- The system shall provide a navigation sidebar or navigation menu.
- The system shall provide an interactive banking dashboard.
- The system shall provide forms for account creation and transactions.
- The system shall provide feedback for successful and unsuccessful operations.
- The system shall provide a dark mode interface.
- The system shall support responsive layouts for different screen sizes.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Structure and layout |
| CSS3 | Styling, responsive design, and themes |
| JavaScript | Application logic and banking operations |
| LocalStorage | Client-side data persistence |

## 📂 Project Structure

```text
bank-management-system/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

## 🚀 Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/bank-management-system.git
```

### 2. Navigate to the Project Directory

```bash
cd bank-management-system
```

### 3. Run the Application

Open `index.html` in your web browser.

You can also use Visual Studio Code with the Live Server extension to run the application locally.

## 🔐 Demo Login

| Field | Value |
|---|---|
| Username | `admin` |
| Password | `1234` |

## 📸 Application Modules

- Dashboard
- Account Management
- Deposits
- Withdrawals
- Transfers
- Transaction History
- Dark Mode

## 🔒 Security Disclaimer

This application is intended for educational and demonstration purposes only.

It is a frontend-only banking simulation and does not implement a real banking backend, secure server-side authentication, encrypted financial storage, or real financial transactions. Login credentials and banking records are managed within the client-side application.

**Do not use this application to store real financial data or conduct real banking activities.**

## 🎯 Project Objective

The objective of this project is to demonstrate the implementation of a simple banking management interface using HTML, CSS, and JavaScript, including account management, transaction processing, data persistence, dashboard statistics, and responsive user interface design.

## 👨‍💻 Author

Developed as a web-based Bank Management System project.

## 📄 License

This project is available for educational and learning purposes. Add a specific open-source license file if you intend to distribute it under a formal license.
