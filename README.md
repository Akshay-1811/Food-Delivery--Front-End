# Food-Delivery--Front-End
# Food Delivery

## Project Description

Dooed Delivery is a food delivery platform built using **JavaScript**, **React**, **HTML**, and **CSS**. This project simulates the front-end interface of a food delivery website, providing features such as exploring menus, placing orders, and managing carts. The app is responsive and designed to deliver a smooth user experience across various devices.

## Features

- Browse and explore different food menus.
- Add items to the cart and manage your orders.
- Place orders and track previous ones.
- User-friendly interface with a clean, responsive design.

## Technologies Used

- **React**: For building reusable UI components and managing application state.
- **JavaScript (ES6)**: Core logic and interactivity.
- **HTML**: Structuring the content of the web pages.
- **CSS**: Styling and ensuring responsiveness.

## Project Structure

```bash
|-- context/
    |-- StoreContext.js        # Manages global state and provides context to components.
|-- components/
    |-- Download.jsx           # Component for the app download section.
    |-- ExploreMenu.jsx        # Displays available food categories and items.
    |-- FoodDisplay.jsx        # Renders the list of food items.
    |-- FoodItem.jsx           # Displays individual food item details.
    |-- Footer.jsx             # Footer section of the page.
    |-- Header.jsx             # Header with navigation and branding.
    |-- LoginPopup.jsx         # Component for user login popup.
    |-- Navbar.jsx             # Navigation bar for the site.
|-- pages/
    |-- Cart.jsx               # Page to display items added to the cart.
    |-- Home.jsx               # Main homepage with an overview of the app.
    |-- MyOrders.jsx           # Displays past user orders.
    |-- PlaceOrder.jsx         # Page to place a new order.
    |-- Verify.jsx             # Page for order verification.
|-- assets/                    # Contains images, icons, and other static assets.
|-- index.css                  # Global styles for the project.
|-- Main.jsx                   # Entry point for the React application.
