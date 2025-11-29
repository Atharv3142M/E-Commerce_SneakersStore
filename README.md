RedStore - E-Commerce Website
RedStore is a fully responsive, front-end e-commerce website template designed for sports wear and accessories. It features a complete shopping flow from product browsing to checkout, simulated user authentication, and a dynamic shopping cart system using browser LocalStorage.
🚀 Features
General
 * Responsive Design: Fully adaptable layout for Desktops, Tablets, and Mobile phones.
 * Mobile Navigation: Toggle menu for smaller screens.
 * Currency: All pricing is formatted in Indian Rupee (₹).
🛍️ Shopping Experience
 * Product Listing: Browse featured and latest products.
 * Sorting: Sort products by Price (Low/High), Popularity, or Rating on the Products page.
 * Product Details: View detailed information, select sizes, and add specific quantities to the cart.
 * Dynamic Cart:
   * Add items with specific sizes and quantities.
   * Persists data using LocalStorage (Cart won't vanish on refresh).
   * Update quantities directly in the cart.
   * Remove items.
   * Real-time calculation of Subtotal, Tax, and Grand Total.
🔐 User Account System (Simulated)
 * Authentication:
   * Register: Create a new account (saved to browser storage).
   * Login: Sign in with your registered credentials.
   * Logout: Securely end the session.
 * Profile Management: View and update your username and email after logging in.
 * Form Toggle: Smooth animation between Login and Register forms.
💳 Checkout Process
 * Billing Form: comprehensive form for address and user details.
 * Order Summary: Displays the final list of items and total cost before placing the order.
 * Payment Options:
   * Cash on Delivery (COD).
   * Credit/Debit Card (Mock fields).
   * UPI (Mock fields).
 * Order Simulation: Validates the cart and form, simulates processing, clears the cart, and redirects to home.
🛠️ Technologies Used
 * HTML5: Semantic structure.
 * CSS3: Styling, Flexbox layout, and Animations.
 * JavaScript (Vanilla): Logic for Cart, Auth, Sorting, and DOM manipulation.
 * Font Awesome: Icons for UI elements.
 * Google Fonts: Poppins font family.
📂 File Structure
/
├── index.html            # Home page (Hero, Featured Products, Testimonials)
├── products.html         # All Products page with Sorting logic
├── products-details.html # Single Product view with "Add to Cart" logic
├── cart.html             # Cart page (View items, Update Qty, Totals)
├── checkout.html         # Billing and Payment page
├── account.html          # Login, Register, and Profile management
├── about.html            # About Us info
├── contact.html          # Contact form
├── style.css             # Main stylesheet
├── README.md             # Project documentation
└── images/               # Product and UI images (logo.png, buy-1.jpg, etc.)

⚡ How to Run
 * Download or Clone the repository.
 * Ensure you have the images folder populated with the necessary assets (logos, product images).
 * Open index.html in any modern web browser (Chrome, Firefox, Edge).
 * No backend server or database is required; it runs entirely in the browser.
📖 Usage Guide
 * Registering: Go to Account, fill in the Register form. Then switch to the Login tab and sign in.
 * Shopping: Go to Products, click on a product image. Select a Size, enter Quantity, and click Add to Cart.
 * Cart: Click the Cart icon in the navbar. You can adjust quantities here.
 * Checkout: Click "Proceed to Checkout". Fill in the mock details.
 * Payment: Select "UPI" or "Card" to see the dynamic fields appear. Click "Place Order" to finish.
👨‍💻 Developer
Developed by Atharv Pose Copyright © 2025
