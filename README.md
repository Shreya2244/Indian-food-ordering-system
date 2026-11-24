## 🍔 Online Food Ordering System (Django)

A full-stack Online Food Ordering System built using Django, Bootstrap, CSS, JavaScript, and MySQL, featuring user authentication, cart management, checkout, order tracking, and a separate Admin Dashboard for managing products and orders.

 ## 🚀 Features
 👤 User Features

User Registration & Login,
View Food Menu,
Add / Remove Items from Cart,
Update Quantity,
Checkout with Address & Phone,
Place Orders,
Cancel Orders (before delivery).

 ## 🛠️ Admin Features (Separate Dashboard)

Secure Admin Login,
Add / Edit / Delete Products,
View All Orders,
Order Status Management,
Dashboard Analytics (Total Orders, Products).

## 🎨 UI & Tech

Responsive UI with Bootstrap,
Custom styling using CSS,
Dynamic cart using JavaScript,
Media handling for food images.

## 🧑‍💻 Tech Stack
Layer	Technology,
Backend	Django (Python),
Frontend	HTML, Bootstrap, CSS, JavaScript,
Database	MySQL,
Authentication	Django Auth,
Media Storage	Django Media Files.

## 📂 Project File Structure

food_project/
│
├── food_ordering/                # Project settings
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── store/                        # Main application
│   ├── migrations/
│   ├── static/
│   │   ├── css/
│   │   │   └── style.css
│   │   └── images/
│   │       └── hero-food.jpg
│   │
│   ├── templates/
│   │   ├── base.html
│   │   ├── home.html
│   │   ├── menu.html
│   │   ├── cart.html
│   │   ├── checkout.html
│   │   ├── orders.html
│   │   ├── login.html
│   │   ├── register.html
│   │
│   │   └── admin/               # Separate Admin Dashboard
│   │       ├── dashboard.html
│   │       ├── products.html
│   │       ├── add_product.html
│   │       ├── edit_product.html
│   │       └── orders.html
│   │
│   ├── admin.py
│   ├── admin_urls.py            # Custom admin routing
│   ├── admin_views.py           # Admin logic
│   ├── apps.py
│   ├── models.py
│   ├── views.py                 # User views
│   ├── urls.py
│   └── tests.py
│
├── media/
│   └── foods/
│       ├── burger.jpg
│       ├── pasta.jpg
│       ├── pizza.jpg
│       └── sandwich.jpg
│
├── manage.py
└── requirements.txt

## 🗂️ Main Modules Explained
 🔐 Authentication

Uses Django’s built-in authentication system,
Login & Register pages styled with Bootstrap,
Session-based cart support.

## 🛒 Cart System

Add items to cart,
Update quantity,
Remove items,
Dynamic total calculation.

## 📦 Order Management

Orders stored in MySQL,
Order items linked to products,
User can view order history,
Cancel order option.

## 🧑‍💼 Separate Admin Dashboard

Not Django default admin,
Custom UI dashboard,
Manage products & orders.

## User Home Page Link : http://127.0.0.1:8000/

<img width="2048" height="2542" alt="Image" src=""C:\Users\shrey\OneDrive\Pictures\Screenshots\Screenshot 2026-11-24 164938.png"" />

<img width="2048" height="2516" alt="Image" src="https://github.com/user-attachments/assets/c3467bf7-d759-4764-a9a3-0be4d8f8818c" />

<img width="2048" height="1808" alt="Image" src="https://github.com/user-attachments/assets/3c74a203-fd4b-4ac4-8935-a9e75c896424" />

<img width="2048" height="1508" alt="Image" src="https://github.com/user-attachments/assets/913971d5-dfcf-4e64-9803-7530a3b9b5a5" />

<img width="1352" height="635" alt="Image" src="https://github.com/user-attachments/assets/92cfb6a8-1caa-4c0f-859d-7c0d1cb8de75" />

<img width="2048" height="1700" alt="Image" src="https://github.com/user-attachments/assets/d19e7b4a-734c-4e8a-859f-22c8ba6ad2da" />

<img width="2048" height="1348" alt="Image" src="https://github.com/user-attachments/assets/53916b1c-9bf3-4f6f-bf8f-bddec28017fe" />

## Admin dashboard Link : http://127.0.0.1:8000/admin-dashboard/

<img width="1366" height="647" alt="Image" src="https://github.com/user-attachments/assets/e6812d02-0b82-4558-beed-b84522ebc02e" />

<img width="1365" height="628" alt="Image" src="https://github.com/user-attachments/assets/335cd3ca-4a08-4425-b618-4c73cdab8c8c" />

<img width="1345" height="630" alt="Image" src="https://github.com/user-attachments/assets/3fee66db-ba9d-417f-8d50-71c9ec8762a1" />

<img width="1366" height="631" alt="Image" src="https://github.com/user-attachments/assets/598aa054-ecfc-4eaf-a452-aa045c60bc41" />

## Django Admin page Link : http://127.0.0.1:8000/admin/ 

<img width="1352" height="634" alt="Image" src="https://github.com/user-attachments/assets/b0e01888-0dc4-4f84-a9e4-b969eaf58f4f" />

<img width="1349" height="638" alt="Image" src="https://github.com/user-attachments/assets/02900f34-6ac4-479a-9412-9c3c93c0dee6" />

<img width="1366" height="632" alt="Image" src="https://github.com/user-attachments/assets/2f72712b-5847-4e04-bc2d-51a2e791d499" />

<img width="1346" height="631" alt="Image" src="https://github.com/user-attachments/assets/389fe5fd-e261-4955-bafd-8c15e9c6daa4" />

<img width="1347" height="646" alt="Image" src="https://github.com/user-attachments/assets/83b391b8-a228-40dd-a99e-92e658e504f5" />

<img width="1345" height="642" alt="Image" src="https://github.com/user-attachments/assets/fcec8352-64b6-4b64-b3f5-54cb85537a55" />

## Database MySQL

<img width="1366" height="697" alt="Image" src="https://github.com/user-attachments/assets/78c04248-b667-4c2e-8098-d898c95702b3" />

<img width="1366" height="693" alt="Image" src="https://github.com/user-attachments/assets/0a4b0137-d365-4d69-8ed9-17c7d3fee0ea" />

<img width="1366" height="702" alt="Image" src="https://github.com/user-attachments/assets/e70c053f-47fb-4b98-908c-474d54af60e0" />

<img width="1366" height="706" alt="Image" src="https://github.com/user-attachments/assets/f7ae2df3-d061-422e-9d68-d48f3364353f" />
