
SwiftCart
Introduction
SwiftCart is a modern e-commerce web application built using Alpine.js for reactive UI components and Tailwind CSS for styling. The app features a product listing with sorting and filtering options, a wishlist, a shopping cart, and a modal for detailed product information. SwiftCart provides a seamless shopping experience with responsive design and easy-to-use navigation.

Technologies Used
Alpine.js: For creating reactive UI components and managing application state.
Tailwind CSS: For styling the application and ensuring a responsive design.
Fake Store API: For fetching product and category data.

Configuration
No additional configuration is required as the application fetches data directly from the CDN and Fake Store API.

Usage
Application Structure
Header: Contains the navigation menu with links to the wishlist, cart, and login page.
Main Content Area: Displays the product listing with sorting and filtering controls.
Product Grid: Shows products with options to add them to the wishlist or cart.
Wishlist and Cart Sections: Display products added to the wishlist and cart respectively.
Product Modal: Shows detailed information about a selected product.

Features
Navigation Menu:

Wishlist Link: Displays the number of items in the wishlist and opens the wishlist section.
Cart Link: Displays the number of items in the cart and opens the cart section.
Login Link: Redirects to the login page (placeholder link).
Search and Filter Controls:

Search Input: Filters product categories based on user input.
Dropdown Menu: Allows selection of product categories.
Sort Buttons: Sort products by price (low to high or high to low).
Reset Button: Resets all filters and sorting options.
Product Grid:

Product Cards: Display product image, title, category, and price.
Wishlist and Cart Buttons: Add or remove products from the wishlist or cart.
Loading Spinner: Displays while data is being fetched from the API.

Product Modal: Provides detailed product information and options to add or remove the product from the wishlist or cart.

Wishlist and Cart Sections:

Product Cards: Display products added to the wishlist or cart.
Back Button: Returns to the main product listing.
Code Overview
Alpine.js Functions
init(): Initializes the app by fetching categories and products.
fetchCategories(): Fetches product categories from the API.
fetchProducts(): Fetches products from the API and applies filters and sorting.
filterCategories(): Filters categories based on the search term.
resetFilters(): Resets all filters and reloads products.
toggleWishlist(productId): Toggles a product in or out of the wishlist.
toggleCart(productId): Toggles a product in or out of the cart.
showWishlistItems(): Displays wishlist items.
showCartItems(): Displays cart items.
openModal(productId): Opens a modal with detailed product information.

This README file provides a comprehensive overview of the SwiftCart project, including setup instructions, usage details, and information on contributing to the project.