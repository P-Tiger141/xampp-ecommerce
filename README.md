# xampp-ecommerce
A simple e-commerce website built using HTML, CSS, PHP, and MySQL on XAMPP. Includes user login, registration, and order management system.
---

## 🚀 Features
- User registration and login system  
- Product listing and ordering  
- MySQL database for users, products, and orders  
- Accessible on LAN (same Wi-Fi)  
- Optional Ngrok setup for public access  

---

## 🧰 Tech Stack
- **Frontend:** HTML, CSS  
- **Backend:** PHP  
- **Database:** MySQL (via phpMyAdmin)  
- **Server:** Apache (XAMPP)

---

## ⚙️ Setup Instructions
1. Install **XAMPP** on your system  
2. Place the project folder in:
C:\xampp\htdocs\xampp-ecommerce

markdown
Copy code
3. Start **Apache** and **MySQL** in XAMPP Control Panel  
4. Open **phpMyAdmin** and create a database named `shopping`  
5. Import or create tables:
- `users(id, username, password, email)`
- `products(id, name, price, stock)`
- `orders(id, user_id, product_id, quantity, order_date)`
6. Access your site:
http://localhost/xampp-ecommerce/

csharp
Copy code
or (from same Wi-Fi):
http://<your-IP>/xampp-ecommerce/

yaml
Copy code

---

## 👥 Contributors
- Prithvi Raj Rana
- [Teammate 1]
- [Teammate 2]
- [Teammate 3]

---

