# E-Shopping-Cart

E-Shopping-Cart is a complete e-commerce system available as both a web application and an Android app. It allows users to browse electronic products, manage their cart, place orders, and track purchases seamlessly across platforms.

## 🚀 Project Overview

A simple yet functional e-commerce platform that enables customers to explore electronic goods, add items to their cart or wishlist, and complete purchases through both web and mobile interfaces.

- View product listings (electronics)
- Browse product details
- Add products to cart or wishlist
- Register / login to their account
- Manage their cart and wishlist
- Checkout & place orders
- View order history and order details
- Track order statuses

It’s a minimal yet functional e-commerce system that demonstrates basic features of an online shopping platform.

## 🧩 Technologies Used

- **Back-end:** PHP  
- **Front-end:** HTML, CSS, JavaScript, Bootstrap  
- **Database:** MySQL (with phpMyAdmin)  
- **Structure:** Plain (native) PHP — no external frameworks  

## 📁 Project Structure

/ (root)  
│  
├── admin/ # Admin-side code (if applicable)  
├── assets/ # Static assets: CSS, JS, fonts, images  
│ ├── css/ # Stylesheets  
│ ├── js/ # JavaScript files  
│ ├── font/ # Fonts  
│ └── img/ # Images  
├── includes/ # PHP includes (header, footer, config, etc.)  
├── layouts/ # Layout templates (if using)  
├── sql/ # Database schema / seed SQL file(s)  
├── bill-ship-addresses.php  
├── category.php  
├── forgot-password.php  
├── index.php  
├── login.php  
├── logout.php  
├── my-account.php  
├── my-cart.php  
├── my-wishlist.php  
├── product-details.php  
├── search-result.php  
├── sub-category.php  
├── track-orders.php  
├── order-history.php  
├── order-details.php  
├── payment-method.php  
├── pending-orders.php  
└── README.md # This file


*(This structure is based on the current repository content.)*

## 🚧 Getting Started / Installation

To run this project locally:

1. Clone the repository  
   ```bash
   git clone https://github.com/TheRuchirShah/E-Shopping-Cart.git
2.  Copy the project folder to your local web server’s root directory (e.g. `htdocs/` in 'XAMPP').
    
3.  Create a MySQL database (e.g. via phpMyAdmin).
    
4.  Import the SQL file(s) from the `sql/` folder to create necessary tables.
    
5.  Update database configuration in the PHP config file (if exists) — set host, username, password, and database name.
    
6.  Open the project in your browser (e.g. `http://localhost/E-Shopping-Cart/`).
    

## ⚙️ Usage

-   Browse the product catalog from homepage.
    
-   Click a product to view details.
    
-   Add product to cart or wishlist.
    
-   Register or log in to your account to manage cart/wishlist or place orders.
    
-   Use “My Cart” to view or update items.
    
-   Proceed to checkout to place an order.
    
-   View past orders in “Order History.”
    
-   Track orders using “Track Orders.”
    

## 🛠️ Potential Improvements (Future Work)

-   Add admin panel for product and order management
    
-   Add user roles (admin / customer)
    
-   Improve security (e.g. input sanitization, password hashing)
    
-   Add payment gateway integration
    
-   Add responsive design improvements for better mobile support
    
-   Add product categories, filters, search enhancements
    

## 📄 License

MIT License (or choose a license if you prefer) — feel free to update this section.


