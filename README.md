# Online Store API

---

### 🎯Purpose

Develop a REST API for an online store to make it easier to buy things.

---

### 📝Description

**The project implements the following functionality:**  
1) Realize a page where all products will be displayed;  
2) Realize the possibility to view information about one product by its id;  
3) Realize the ability to add an item to the cart;  
4) Realize the possibility to view your shopping cart;  
5) Implement the ability to check out for the entire cart.

---

### 🛠️Stack

**Languages**: Python, JavaScript;  
**Frameworks**: Django, Django REST Framework;  
**Libraries**: djoser, psycopg2, drf-nested-routers, python-dotenv;  
**Database**: PostgreSQL;
**Tools**: Docker, docker-compose.

---

### ⚙️Installation

---

1) **Clone the repository**: ```git clone https://github.com/shoksdev/online-store-api.git```  
2) **Go to the project folder**: ```cd project```  
3) **Start the project with superuser creation**: ```docker-compose run django python manage.py createsuperuser```  
4) **Bring the project**: ```docker-compose up```  

---

### 📙Guidelines for use

1) Go to http://127.0.0.1:8000/api/v1/products/ for a list of products;
2) Go to the page http://127.0.0.1:8000/api/v1/products/int:pk/ to work with an individual product;  
3) Go to http://127.0.0.1:8000/api/v1/carts/ page and send POST request -> your cart will be created;  
4) Go to http://127.0.0.1:8000/api/v1/carts/int:id_your_cart/items/ and enter product id and quantity -> this product will be added to your cart;  
5) Go back to http://127.0.0.1:8000/api/v1/carts/int:id_your_cart/items/ and see the list of items in your cart;  
6) Go to http://127.0.0.1:8000/api/v1/orders/ and enter the id of the cart -> your order will be created, you will be able to see the list of all your orders and their contents, your cart will be cleared;  

---

#### Thank you very much for taking the time to share this repository and my profile in general. All the best!
