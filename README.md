# E-Commerce Website

This project is an E-commerce website developed using Django framework, Python, and SQLite. It provides users with a platform to browse through various products, add them to their cart, and complete the checkout process. The website includes features such as user authentication, product categories, cart management, and order placement.

# Technologies Used
-Python
-Django framework
-SQLite

#Features
-**User authentication**: Users can create accounts, log in, and log out securely.
-**Product browsing**: Users can browse through a list of products categorized by type.
-**Cart management**: Users can add products to their cart, remove products, and adjust quantities.
-**Checkout process**: Users can proceed to checkout, provide shipping details, and place orders securely.
-**Admin interface**: Admins can add, remove, and modify products, categories, orders through an intuitive interface.

## Installation

1. Clone the repository to your local machine.
2. Create a virtual environment:
    
    python3 -m venv myenv
    
3. Activate the virtual environment:
    - On Windows:
        
        myenv\Scripts\activate
        
    - On macOS and Linux:
        
        source myenv/bin/activate
        
4. Install Django and other dependencies:
    
    pip install -r requirements.txt
    
5. Start the development server:
    
    python manage.py runserver
    
7. Access the website through your browser at [http://localhost:8000](http://localhost:8000).

## Usage

- Navigate to the homepage to browse products and add them to your cart.
- Register or log in to manage your cart, place orders, and view order history.
- Admins can access the admin interface at `/admin` to manage products.
