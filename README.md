# Develop-E-commerce-Website
## Project Overview
This project is a simple and responsive e-commerce website built with HTML, CSS, and JavaScript. It allows users to browse products, add items to a shopping cart, and proceed to checkout. Product data is dynamically fetched from the **Fake Store API**.

## Features
- **Product Listing**: Users can browse a list of products displayed in a grid layout.
- **Product Details**: Each product has a detailed view with an image, description, and price.
- **Shopping Cart**: Users can add products to a shopping cart, adjust quantities, and remove items.
- **Responsive Design**: The website is optimized for both desktop and mobile devices.

## Setup and Installation

### Prerequisites
- **Text Editor**: A code editor like VS Code or Sublime Text.
- **Web Browser**: Any modern web browser (e.g., Chrome, Firefox).
- **Internet Connection**: Required to fetch data from the Fake Store API.

### Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Akashparmar1/Develop-E-commerce-Website
   ```

2. **Navigate to the Project Directory**
   ```bash
   cd e-commerce-website
   ```

3. **Open the Project in a Browser**
   Open `index.html` in your preferred web browser to view the website locally.

Alternatively, if you’re using a live server extension in your code editor:
- Open `index.html` with **Live Server** to start a local development server, which will automatically reload changes.

## Project Structure

- **index.html**: The homepage that displays the main product list.
- **about.html**: A product detail page to display information about a specific product.
- **cart.html**: The shopping cart page that allows users to review and manage their selected products.
- **sing-up.html**: The checkout page for completing a purchase.
- **styles/**: Folder containing CSS files for layout and styling.
  - **style.css**: The main stylesheet.
- **scripts/**: Folder containing JavaScript files for functionality.
  - **app.js**: Main script for handling product display and interactions.
  - **cart.js**: Manages cart functionality like adding and removing items.


## JavaScript Functionality

1. **Fetching Data from the API**
   - Product data is retrieved from the Fake Store API (`https://fakestoreapi.com/products`) using `fetch()` in JavaScript.

2. **Displaying Products**
   - Products are dynamically rendered on `index.html` by injecting HTML into the DOM based on the fetched data.

3. **Shopping Cart Management**
   - Cart data is stored in `localStorage` to ensure persistence even if the page is reloaded.

4. **Responsive Design**
   - CSS media queries ensure the layout adapts for different screen sizes.

## Deployment Instructions

### Deploying on GitHub Pages

1. **Push Your Code to GitHub**
   - If your repository is private, make it public or deploy from an accessible branch.

2. **Go to GitHub Pages Settings**
   - Go to your repository settings, scroll to **GitHub Pages**, and select the branch to deploy from (typically `main` or `master`).

3. **Access the Site**
   - After deployment, GitHub will provide a URL where the website can be accessed.

     `https://github.com/Akashparmar1/Develop-E-commerce-Website`

---

## Future Enhancements
Potential features to add in the future:
- **User Authentication**: Allow users to create accounts and save cart items.
- **Payment Integration**: Integrate a payment gateway for handling transactions.
- **Product Filtering**: Enable sorting and filtering of products by category and price.

## Acknowledgments
- Fake Store API: Used for sample product data.
- GitHub Pages: Hosting platform for this project.

