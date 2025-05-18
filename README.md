# 🧾 Sale Order Management SPA

A responsive and user-friendly Single Page Application (SPA) for managing sale orders, built using **React**, **Chakra UI**, **React Router DOM**, **React Hook Form**, and **TanStack React Query**.

---

## 🚀 Features

- 🔐 Login screen with form validation
- 🌗 Light/Dark theme toggle
- 🧭 Tabbed views for navigation:
  - Orders list
  - Create/Edit order modals
- 🧾 Sale Order Form (Modal-based)
- ✅ Product multi-select input
- 📦 React Query for API data fetching and mutation
- 🎯 Form handling with React Hook Form + Chakra UI integration

---

## 🛠 Tech Stack

- **React** (Vite)
- **Chakra UI** for UI components and theming
- **React Router DOM** for navigation
- **TanStack React Query** for async data management
- **React Hook Form** for form handling
- **Vite** for fast bundling and dev experience

---

## 📂 Project Structure

sale-order-management/
├── public/
├── src/
│ ├── components/
│ │ ├── Login.jsx
│ │ ├── Orders.jsx
│ │ ├── SaleOrderModal.jsx
│ │ ├── EditOrderModal.jsx
│ │ └── ThemeToggle.jsx
│ ├── App.jsx
│ ├── ChakraProviderWrapper.jsx
│ ├── main.jsx
│ └── index.css
├── .gitignore
├── index.html
├── package.json
├── vite.config.js
└── README.md

---

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/Balushiva/sales-order-management.git
# Navigate to the project directory
cd sale-order-management

# Install dependencies
npm install

# Start the development server
npm run dev

