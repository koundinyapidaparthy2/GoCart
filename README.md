# React Native E-Commerce App

## Overview
This is a fully functional eCommerce application built with React Native. Users can log in using **Google** and **Apple authentication** (via Clerk), browse products, add items to their cart, and complete purchases.

## Screen Shots

### Auth Screen
#### Allows users to sign in using Google or Apple authentication via Clerk.

<img src="images/AuthScreen.jpg" alt="Auth Screen" width="200" />


### Home Screen
#### Displays a list of available products with essential details.

<img src="images/AuthScreen.jpg" alt="Auth Screen" width="200" />

### Product Screen
#### Shows detailed information about a selected product, including images, price, and description.

<img src="images/ProductScreen.jpg" alt="Product Screen" width="200" />

### Cart Screen
#### Displays products added to the cart and provides an option to proceed to checkout.

<img src="images/CartScreen.jpg" alt="Cart Screen" width="200" />

## Features
- **User Authentication**: Google and Apple login powered by **Clerk**.
- **State Management**: Implemented with **Redux** for efficient data flow.
- **Product Listing**: Display products dynamically.
- **Cart Management**: Add, remove, and update items in the cart.
- **Checkout Process**: Secure purchase flow.
- **Firebase Integration**: Real-time data updates and secure transactions.

## Tech Stack
- **React Native**: Cross-platform development.
- **Clerk**: Authentication management.
- **Redux**: State management.
- **Firebase**: Database and backend services.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo-url.git
   ```
2. Navigate to the project folder:
   ```sh
   cd ecommerce-app
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
4. Run the application:
   ```sh
   npx react-native run-android  # For Android
   npx react-native run-ios      # For iOS
   ```


