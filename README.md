Django Python License

[Luxshop](https://luxshop.crsyndicate.info/)

A full-featured e-commerce platform built with Django, featuring user authentication, product management, shopping cart, order processing, and an admin dashboard.

✨ Features
🛍️ Customer Features
User Registration & Authentication: Secure login and signup with role-based access (Admin/Customer)
Product Browsing: Browse products by categories with detailed product pages
Shopping Cart: Add, update, and remove items from cart
Wishlist: Save favorite products for later
Order Management: Place orders, track order history, and view order details
Reviews & Ratings: Leave reviews and ratings for products
Contact Support: Send messages to administrators
Coupon System: Apply discount coupons during checkout
👨‍💼 Admin Features
Dashboard: Overview of sales, orders, and users
Product Management: Add, edit, and delete products and categories
Order Management: View and update order statuses
User Management: Manage customer accounts
Message Handling: Respond to customer inquiries
Analytics: Monitor site performance and sales
🛠️ Tech Stack
Backend: Django 6.0
Database: SQLite (development), PostgreSQL (production recommended)
Frontend: HTML, CSS, JavaScript, Bootstrap
Image Handling: Pillow
Static Files: WhiteNoise
Deployment: Gunicorn
Other: Django Admin, Authentication, Sessions
🚀 Installation
Prerequisites
Python 3.8 or higher
Git
Setup Instructions
Clone the repository

git clone https://github.com/RabbiPrimon/LuxShop-E-commerce-Platform.git
cd personal-e-commarce-website
Create a virtual environment

python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
Install dependencies

pip install -r requirements.txt
Run migrations

python manage.py migrate
Create a superuser

python manage.py createsuperuser
Collect static files

python manage.py collectstatic
Run the development server

python manage.py runserver
Access the application

Main site: http://127.0.0.1:8000/
Admin panel: http://127.0.0.1:8000/admin/
📖 Usage
For Customers
Register an account or login
Browse products and add to cart
Proceed to checkout and place orders
Track orders in your dashboard
Leave reviews for purchased products
For Admins
Login to admin panel
Manage products, categories, and orders
Respond to customer messages
Monitor site analytics
📁 Project Structure
personal-e-commarce-website/
├── ecommarce/                 # Django project settings
├── myapp/                     # Main Django app
│   ├── models.py             # Database models
│   ├── views.py              # View functions
│   ├── templates/            # HTML templates
│   ├── static/               # Static files (CSS, JS, images)
│   └── migrations/           # Database migrations
├── media/                    # User-uploaded files
├── staticfiles/              # Collected static files
├── manage.py                 # Django management script
├── requirements.txt          # Python dependencies
└── README.md                 # This file
🔧 Configuration
Environment Variables
For production deployment, set the following environment variables:

DEBUG=False
SECRET_KEY=your-secret-key
DATABASE_URL=your-database-url
Database
The project uses SQLite by default. For production, consider switching to PostgreSQL.

🤝 Contributing
Fork the repository
Create a feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request
