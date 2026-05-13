# WoolzHub E-Commerce Website

A modern WoolzHub E-Commerce Website built with React.js and Bootstrap 5, featuring a client-side store and admin panel.

## Features

### Client Side (Customer)
- **Home Page** - Hero banner, categories, featured products, sale banner, testimonials
- **Product Listing** - Grid layout with filters (category, price, rating), search
- **Product Details** - Image, description, sizes, quantity, reviews, add to cart
- **Cart** - Update quantity, remove items, view total
- **Checkout** - Shipping info, payment method (Cash on Delivery / Card)
- **Login/Register** - Customer authentication
- **Wishlist** - Add products to wishlist (heart icon)

### Admin Panel
- **Dashboard** - Stats cards, sales charts (Chart.js)
- **Products** - Add, Edit, Delete products
- **Orders** - View and update order status (Pending/Shipped/Delivered)
- **Users** - View and delete users

## Tech Stack

- React 19
- React Router 7
- Bootstrap 5
- FontAwesome
- Chart.js (admin dashboard)
- Vite

## Getting Started

```bash
# Install dependencies (if not already done)
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Admin Access

Login with:
- **Email:** admin@woolzhub.com
- **Password:** admin123

For regular customer access, use any email/password to register or login.

## Project Structure

```
src/
├── components/       # Navbar, Footer, ProductCard
├── pages/            # Home, Products, ProductDetails, Cart, Checkout, Login, Register
├── admin/            # Dashboard, ProductsAdmin, OrdersAdmin, UsersAdmin, AdminLayout
├── context/          # CartContext, AuthContext
├── data/             # mockData.js
├── App.jsx
└── main.jsx
```

## Winter Theme Colors

- Dark Blue: #0d2137
- Blue: #1e3a5f
- Ice Blue: #87ceeb
- White & Light Grey
