# Django E-Commerce Website

## Overview

This is a feature-rich e-commerce website built using Django. The platform allows users to browse products, add them to a shopping cart, and complete purchases. It also supports user registration, authentication, email verification, and order tracking. The admin panel is used for managing products, categories, and orders. The website is designed to ensure an efficient and secure shopping experience.

![image](https://github.com/user-attachments/assets/dee5f208-d52b-40eb-8c82-3293a172eca3)
<img width="3420" height="1924" alt="image" src="https://github.com/user-attachments/assets/e320681b-092e-446a-acb1-0a864afe2711" />




## Features

### General Features
- **User Registration & Authentication**: Users can register, log in, and log out. New accounts require email verification for activation.
- **Product Browsing**: Users can browse products by category or view detailed information about a specific product.
- **Shopping Cart**: Add, update, and delete items from the shopping cart using AJAX for a seamless user experience.
- **Order Management**: Users can place orders, manage shipping addresses, and track order statuses.
- **Payment**: Integration of a checkout process and payment success/failure handling.
- **Admin Panel**: Admins can manage products, categories, users, and orders.

### Authentication Features
- Email verification system using Django's token generator.
- Profile management and account deletion functionalities.
- Dashboard for authenticated users.

### Payment and Shipping
- Authenticated users can save shipping addresses for faster checkout.
- Guest users can complete orders without creating an account.
- Orders and their items are logged for easy tracking.

## Installation

1. Clone the repository:
```
   git clone https://github.com/Mikheil-U/Ecommerce_Django.git
   cd Ecommerce_Django
```
2. Create a virtual environment and install dependencies:
```
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```
3. Apply Migrations: 
```
python manage.py migrate
```
4. Run the development server:
```
python manage.py runserver
```
5. Open the website in your browser at http://127.0.0.1:8000.

## File Structure
### Key Directories
* ecommerce/account/: Handles user authentication, registration, profile management, and email verification.
* ecommerce/payment/: Manages the checkout process, order creation, and payment status handling.
* ecommerce/shopping_cart/: Manages the shopping cart operations, including adding, updating, and deleting items.
* ecommerce/store/: Handles product browsing, category filtering, and displaying product details.

<img width="2478" height="1918" alt="image" src="https://github.com/user-attachments/assets/387e2b9d-5259-4960-8644-45fc4f178560" />
<img width="2526" height="1922" alt="image" src="https://github.com/user-attachments/assets/64a67f5c-0fdb-4b1e-9cc3-377a7795b4ca" />
<img width="1302" height="962" alt="image" src="https://github.com/user-attachments/assets/0a31e61e-6831-473b-9b59-88f2c99c45df" />
<img width="1300" height="951" alt="image" src="https://github.com/user-attachments/assets/7d547ea6-f821-48cb-9578-a8796c9cfb4c" />
<img width="773" height="955" alt="image" src="https://github.com/user-attachments/assets/252a8394-1b15-4d1c-bc28-d2aae6da5a0b" />





















