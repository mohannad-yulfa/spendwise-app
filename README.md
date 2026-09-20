# 💰 SpendWise

### Personal Finance Management App

**SpendWise** is a personal finance management application built with **Flutter**, designed to help users track their income and expenses, manage their wallets, organize their budgets, and work toward their financial goals through a clean and intuitive mobile experience.

---

## 📱 Overview

Managing personal finances can become complicated when income, expenses, savings, debts, and financial obligations are spread across different places.

**SpendWise** brings these activities together in one application, providing users with a clear overview of their financial activity and helping them organize their money more effectively.

---

## ✨ Features

### 💸 Expense Management

* Add and manage expenses
* Categorize expenses
* Track spending activity
* Support for expense tags
* Track expenses from different wallets

### 💰 Income Management

* Add and manage income
* Organize income sources
* Support for fixed income
* Track financial activity over time

### 👛 Wallet Management

* Create and manage wallets
* Track wallet balances
* Organize financial accounts
* Support for savings wallets

### 📊 Budget Management

* Create category-based budgets
* Define budget percentages
* Set budget start and end dates
* Monitor spending against budgets

### 🎯 Savings Goals

* Create savings goals
* Track progress toward financial targets
* Manage savings separately from regular spending

### 🤝 Shared Debts

* Track shared debts
* Organize money owed between people
* Keep debt information in one place

### 🏷️ Categories & Tags

* Organize transactions using categories
* Add tags for more detailed financial organization
* Make transactions easier to search and understand

### 📱 Dashboard

* Overview of financial activity
* Balance information
* Income and expense summaries
* Financial insights in one place

---

## 🛠️ Technologies

* **Flutter**
* **Dart**
* **GetX**
* **Isar**
* **Clean Architecture**
* **REST API**
* **Git / GitHub**

---

## 🏗️ Architecture

The project follows a structured architecture designed to keep the codebase maintainable and scalable.

```text
Presentation
     ↓
ViewModel / Controller
     ↓
Use Cases
     ↓
Repository
     ↓
Data Sources
     ↓
Local Database / API
```

The application also uses an **offline-first** approach for local data handling, allowing important financial data to be stored locally and synchronized with the backend.

---

## 🗄️ Local Data & Synchronization

SpendWise uses **Isar** for local data storage.

The synchronization system is designed around entities that can track their local and server state.

Examples include:

* Wallets
* Expenses
* Income
* Fixed Obligations
* Budgets
* Savings Goals
* Tags

Synchronization-related information can include:

```text
isSynced
isDeleted
createdAt
updatedAt
syncAttempts
lastSyncError
```

This approach helps the application handle local changes and synchronize them with the backend.

---

## 📸 Screenshots

https://github.com/user-attachments/assets/10894eef-d079-4791-aeb4-f4c81c7e6840

<img width="4085" height="6113" alt="spendwiseUi_UX pdf" src="https://github.com/user-attachments/assets/c2415424-5c2b-42c5-b5a9-acf72ab03f7a" />


```text
screenshots/
├── dashboard.png
├── wallets.png
├── expenses.png
├── income.png
├── budgets.png
└── savings.png
```

Example:

![SpendWise Dashboard](screenshots/dashboard.png)

---

## 🎥 Demo


https://github.com/user-attachments/assets/332eb395-1988-4374-8676-c02bfe505b4b


---

## 🚀 Getting Started

### Prerequisites

Make sure you have:

* Flutter SDK
* Dart SDK
* Android Studio or VS Code
* Android SDK

### Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/spendwise.git
```

Navigate to the project:

```bash
cd spendwise
```

Install dependencies:

```bash
flutter pub get
```

Run the application:

```bash
flutter run
```

---

## 📂 Project Structure

```text
lib/
│
├── core/
│   ├── data/
│   ├── services/
│   ├── theme/
│   └── ...
│
├── features/
│   ├── wallet/
│   ├── expense/
│   ├── income/
│   ├── budget/
│   ├── savings/
│   └── ...
│
└── main.dart
```

---

## 🎓 Project

SpendWise was developed as a university software engineering project with a focus on building a practical personal finance application using Flutter and modern application architecture.

---

## 👨‍💻 Developer

**Mohannad Hisham Al-Hajja**

Flutter Developer focused on building modern mobile applications with Flutter and Dart.

### Skills demonstrated in this project

* Flutter application development
* Dart
* Mobile UI/UX
* Clean Architecture
* Local database management
* Offline-first application design
* API integration
* State management
* Data synchronization
* Git & GitHub

---

## 📌 Project Status

🚧 **Actively developed**

The project may continue to receive improvements, UI refinements, bug fixes, and additional features.

---

## ⭐ Support

If you find the project interesting, consider giving it a ⭐ on GitHub.
