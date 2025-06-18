# Front-End Development React Project - Houseplant Shopping App

Welcome to **Paradise Nursery**, an interactive and responsive frontend shopping application built with React. This project is the final submission for a frontend development course, designed to provide a fully functioning e-commerce experience for browsing, selecting, and managing a cart of houseplants.

The goal of this project is to simulate a real-world online shopping platform with an elegant user interface and intuitive interactions. Users can explore a curated selection of indoor plants categorized by type, view detailed descriptions and pricing, and effortlessly add plants to their cart. The dynamic cart interface allows for easy quantity adjustments and displays a running total, providing users with an efficient and enjoyable shopping experience. The project emphasizes modular React component design, effective state management with Redux, and a responsive layout adaptable to various screen sizes. This project also showcases modern frontend development practices.

## Project Overview

Paradise Nursery allows users to:

* Browse a selection of beautiful houseplants
* View plants by category with images, descriptions, and prices
* Add and remove plants from a dynamic shopping cart
* Adjust quantities and view total cost before checkout

## Website

Visit the live app here: [https://czhao-dev.github.io/React-Web-App/](https://czhao-dev.github.io/React-Web-App/)

## Features Breakdown

### Landing Page

The landing page features a visually appealing background image that sets the tone for the shopping experience. It includes a welcoming paragraph introducing users to the Paradise Nursery brand, helping to establish a friendly and inviting atmosphere. The company name is prominently displayed, reinforcing brand identity, and a **Get Started** button directs users seamlessly to the product listing page.

### Product Listing Page

This page showcases a curated selection of at least six houseplants, grouped into three or more distinct categories. Each plant item is presented with a thumbnail image, the plant's name, its price, and an **Add to Cart** button. The user interface ensures that each category header is centered and clearly separated for better readability. A dynamic cart icon in the header updates in real time to reflect the number of items added, enhancing user awareness and interaction.

### Shopping Cart Page

The shopping cart page displays a detailed summary of the user's selected items. Each entry includes a thumbnail image, the product name, unit price, and quantity. Users can easily increase or decrease the quantity of each plant using intuitive controls. The page also shows the total price per item and provides a remove button to delete individual items. At the bottom of the cart, a summary shows the total quantity of plants and the overall cost. A **Continue Shopping** button allows users to return to the product listing, while a **Checkout** button displays a "Coming soon" alert when clicked.

### State Management

The cart functionality is powered by Redux, which manages global application state, ensuring a consistent shopping experience across components. UI-specific behaviors, such as disabling the **Add to Cart** button for items already in the cart, are managed through local component state, providing a responsive and intuitive user interface.

## Technologies Used

* React (JSX, functional components, hooks)
* Redux Toolkit
* CSS for layout and styling
* SVG and image assets

## Requirements Met

* Landing page with company branding and intro
* Product listing with category filtering and details
* Add/remove items to/from cart
* Quantity control and price calculation
* Dynamic cart icon update
* Styled and responsive layout

## License

This project is open source and available under the [Apache 2.0 License](LICENSE).
