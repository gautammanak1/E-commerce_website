# E-Commerce Website

[![React](https://img.shields.io/badge/React-18.1-61DAFB?logo=react&logoColor=white)](https://reactjs.org/)
[![React Router](https://img.shields.io/badge/React_Router-6-CA4245?logo=reactrouter&logoColor=white)](https://reactrouter.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

A fully functional e-commerce web application built with React featuring product browsing, detailed product views, and a shopping cart with real-time state management using React Context API.

## Features

- **Product Catalog** — Browse a curated list of products with images, names, and pricing
- **Product Details** — View detailed product information including descriptions and categories
- **Shopping Cart** — Add, remove, and adjust item quantities with live price calculations
- **Cart Total** — Real-time total price updates as items are added or removed
- **State Management** — Global cart state using React Context API and hooks
- **Client-Side Routing** — Seamless navigation between pages without page reloads
- **404 Page** — Custom not-found page for invalid routes
- **Responsive Design** — Works across desktop, tablet, and mobile devices

## Tech Stack

| Technology | Purpose |
|-----------|---------|
| **React 18** | Component-based UI framework |
| **React Router v6** | Client-side routing and navigation |
| **Context API** | Global state management for cart |
| **Fake Store API** | Product data source |
| **CSS Modules** | Component-scoped styling |

## Project Structure

```
E-commerce_website/
├── public/
├── src/
│   ├── components/
│   │   ├── item/            # Product card component
│   │   └── navbar/          # Navigation bar with cart count
│   ├── context/
│   │   └── cart.js          # Cart context provider
│   ├── pages/
│   │   ├── cart/            # Shopping cart page
│   │   ├── product/         # Single product detail page
│   │   ├── products/        # Product listing page
│   │   └── not-found/       # 404 page
│   ├── services/
│   │   └── fake-store-api.js  # API service layer
│   ├── App.js               # Root component with routing
│   └── index.js             # Entry point
├── package.json
└── README.md
```

## Getting Started

### Prerequisites

- Node.js 14+
- npm or yarn

### Installation

```bash
git clone https://github.com/gautammanak1/E-commerce_website.git
cd E-commerce_website
npm install
npm start
```

The app will open at [http://localhost:3000](http://localhost:3000).

## API

This app uses the [Fake Store API](https://fakestoreapi.com/) to fetch product data including titles, prices, descriptions, images, and categories.

## License

This project is open source and available under the [MIT License](LICENSE).
