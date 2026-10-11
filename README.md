# 🌾 Gramora AI — Frontend

**AI-Powered Rural Grocery Delivery & Intelligent Inventory Management System**

Gramora AI is a rural grocery delivery platform designed to make grocery shopping easier for village communities. The frontend provides a simple, user-friendly interface for browsing groceries, adding products to a cart, placing orders, and viewing order information.

## 🚀 Features

- **Modern User Interface** — Clean, responsive design with a fresh green theme.
- **Product Browsing** — View grocery products and their prices.
- **Search and Categories** — Find groceries using search and category filters.
- **Shopping Cart** — Add products and manage quantities.
- **Delivery Charges** — Free delivery for orders of ₹99 or more; ₹10 delivery charge below ₹99.
- **Order Placement** — Submit grocery orders through the application.
- **Order Tracking** — View order information using an order ID.
- **Inventory Insights** — Display inventory-related information supported by the backend.
- **Backend Integration** — Communicate with the Spring Boot backend APIs.

## 🛠️ Technology Stack

- React.js
- Vite
- JavaScript
- HTML5
- CSS3
- REST API integration

## 📁 Project Structure

```text
gramora-frontend/
├── public/
├── src/
│   ├── assets/
│   ├── App.jsx
│   ├── App.css
│   ├── main.jsx
│   └── index.css
├── index.html
├── package.json
├── package-lock.json
├── vite.config.js
└── README.md
```

*Note: The exact folders and files may differ slightly depending on your current project.*

## ⚙️ Prerequisites

Install the following:

- Node.js
- npm
- Git
- Visual Studio Code

## ▶️ How to Run the Frontend

### 1. Clone the repository

```bash
git clone https://github.com/ayeshaayshu2101-boop/GramoraAI-frontend.git
cd GramoraAI-frontend
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start the development server

```bash
npm run dev
```

### 4. Open the application

Open the local URL displayed in your terminal, usually:

```text
http://localhost:5173/
```

Keep the terminal running while using the application.

## 🔗 Backend Integration

The frontend is designed to connect to the Gramora AI Spring Boot backend.

**Backend repository:** [GramoraAI-backend](https://github.com/ayeshaayshu2101-boop/GramoraAI-backend)

The backend typically runs at:

```text
http://localhost:8080
```

Ensure that the backend and MySQL database are running and that the API configuration matches your local setup.

## 🧪 Testing

Test the following features in the browser:

- Browse and search grocery products.
- Filter products by category.
- Add products to the cart and update quantities.
- Verify delivery charges.
- Place an order and check the order information.
- Verify backend connectivity and inventory features.

## 🎯 Project Objective

Gramora AI aims to make grocery shopping convenient for rural communities while supporting smarter inventory management and helping small grocery businesses reduce stock waste.

## 👩‍💻 Developer

**GitHub:** [@ayeshaayshu2101-boop](https://github.com/ayeshaayshu2101-boop)

## 📄 License

This project is currently intended for educational and demonstration purposes. Add a license if you plan to distribute or reuse the project publicly.
