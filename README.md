# 💰 Dividi

A simple and modern **bill-splitting app** built with **Expo** and **React Native Web**, designed for friends and groups in **Portugal** 🇵🇹.  
Users can easily track shared expenses, see who owes who, and even settle payments through **MB WAY**.

---

## ✨ Features

- 🪄 **No account needed** — just your name and phone number
- 👥 **Create or join groups** for trips, dinners, or shared houses
- 💵 **Add expenses** and select who paid and who participated
- 📊 **Automatic balance calculation** (who owes who)
- 📱 Works as both a **mobile app** and **PWA (Progressive Web App)**
- 💸 **MB WAY deep link support** _(coming soon)_

---

## 🧭 App Structure

| Screen                 | Description                             |
| ---------------------- | --------------------------------------- |
| **Onboarding**         | User enters name and phone number       |
| **Groups List (Home)** | Shows all groups and balances           |
| **Create Group**       | Add a new group and invite friends      |
| **Group Details**      | Tabs for Expenses, Summary, and Members |
| **Add Expense**        | Add who paid and how it’s split         |
| **Summary**            | See who owes who and simplify payments  |

---

## 🛠️ Tech Stack

- [Expo](https://expo.dev) – Build once, run anywhere
- [React Native](https://reactnative.dev) – UI components
- [React Native Web](https://necolas.github.io/react-native-web/) – Web/PWA support
- [Firebase (planned)](https://firebase.google.com) – Authentication & storage
- [Tailwind CSS (optional)](https://tailwindcss.com) – Fast styling
- [Vercel](https://vercel.com) – PWA hosting

---

## 📦 Project Structure

/dividi/
├── app/ # Main screens
│ ├── index.tsx # Groups list (Home)
│ ├── group/
│ │ └── [id].tsx # Group details screen
│ └── add-expense.tsx # Add expense form
├── components/ # Reusable UI components
│ ├── GroupCard.tsx
│ ├── ExpenseItem.tsx
│ └── AddExpenseModal.tsx
├── assets/ # Images, icons, splash screens
│ ├── icon.png
│ ├── splash.png
│ └── favicon.png
├── app.config.js # Expo configuration
└── package.json # Project dependencies

---

## 💡 Future Plans

🔐 Firebase phone authentication

💸 MB WAY integration (via deep link)

🔔 Notifications for new expenses

📅 Group filters by month or event

🌑 Dark mode

---

## 🪪 License

This project is licensed under the MIT License — free to use and modify.

---

## 🧾 TL;DR

> “Contas Divididas” makes splitting bills **simple, friendly, and fast** —  
> No logins, no stress. Just add, split, and settle. 💶
