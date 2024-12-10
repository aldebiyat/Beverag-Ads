# Heaven’s Elixir Order Management System

A web-based platform designed to manage orders for the “Heaven’s Elixir” product line. The project includes features for creating, listing, and managing orders using a file-based storage system for simplicity and efficiency.

## Overview

This project is a lightweight, server-side rendered application built using Next.js. It provides an intuitive user interface and backend logic to manage customer orders, with features such as order creation, listing, and detailed views.

## Purpose

- Demonstrate clean code architecture.
- Implement a file-based storage solution.
- Showcase functional components, testing, and modular structure.

## Features

### Order Management

- Create, list, and view orders.
- Display order details including confirmation numbers.

### Reusable Components

- Navbar, Footer, Modal, and OrderCard components.

### Error Handling

- User-friendly messages for fetch errors or empty states.

### Testing

- Comprehensive unit tests using Jest and @testing-library/react.

## Technologies Used

- Frontend: React, TypeScript, Next.js
- Backend: API Routes (Next.js)
- Styling: Tailwind CSS
- Storage: File-based storage.
- Testing: Jest, React Testing Library

## Getting Started

```bash
yarn install
yarn dev
```

## For Testinng Purposes.

```bash
yarn install --save-dev @testing-library/jest-dom --legacy-peer-deps
yarn test
```

## For Production Deployment.

- Create and .env file and add.

```bash
PUBLIC_BASE_URL='Your value.'
```

## Requirements

### Create a landing page that

- Tells the visitor what your drink is called
- Includes an image (or images) that has your drink in it.
- Describe the drink so everyone understands why it’s the greatest beverage ever.
- A privacy focused “pay me later” order form that contains the following:
- Customers name
- Quantity of drinks to purchase
- City
- State/Province
- Country
- An order button

### After ordering

- Confirmation that the order succeeded
- Provide order confirmation number
- Provide unique URL to see order confirmation & details
