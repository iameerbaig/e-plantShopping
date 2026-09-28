# e-plantShopping — Paradise Nursery

**Paradise Nursery** is a React + Redux front-end shopping cart application built for the `e-plantShopping` repository. It lets customers browse a curated catalog of houseplants organized by category, add their favorites to a shopping cart, and manage cart quantities before checkout.

## Overview

The app has three main pages:

- **Landing Page** — introduces Paradise Nursery with a background image, company name, and a short description of the business, along with a "Get Started" button to begin shopping.
- **Product Listing Page** — displays houseplants grouped into multiple categories, each with a thumbnail, name, price, and an "Add to Cart" button.
- **Shopping Cart Page** — shows every item added to the cart, including thumbnail, name, unit price, and item total, with controls to increase or decrease quantity, remove an item, view the overall cart total, continue shopping, or proceed to checkout.

A header with a dynamic shopping cart icon (showing the total number of items) and navigation links appears on both the Product Listing and Shopping Cart pages.

## Tech Stack

- React
- Redux Toolkit (cart state management via `CartSlice.jsx`)
- Vite
- CSS

## Getting Started

```bash
npm install
npm run dev
```

## Deployment

This project is deployed using GitHub Pages.

## Repository

GitHub Repository: [https://github.com/iameerbaig/e-plantShopping](https://github.com/iameerbaig/e-plantShopping)
