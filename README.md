# 🛍️ Geer Intern E-Commerce Project

Welcome to the **Geer Intern E-Commerce Project** — a modern, full-stack e-commerce site built during my internship task. Inspired by [Geer.in](https://geer.in), this platform is designed using HTML, CSS, Bootstrap, JavaScript, Node.js, Express, and MongoDB Atlas.

> ✅ Live Demo: [Visit Website](https://geer-intern-ecommerce-project.onrender.com)

---

## ✨ Features

- 💫 **Animated Welcome Page**  
- 📦 **Product Listing Page**  
- ➕ **Add Product Form (POST API)**  
- 🛍 **Fully Functional Cart System**
- 🔎 **Filter/Search Products**
- ♻️ **Update & Delete Products (via DB/optionally via API)**
- 🧮 **Total Cart Calculation**
- 💖 **Beautiful pink-themed modern design**
- 📱 **Responsive layout with Bootstrap**

---

## 🚀 Tech Stack

| Frontend       | Backend           | Database         | Deployment |
|----------------|--------------------|------------------|------------|
| HTML, CSS, JS  | Node.js + Express  | MongoDB Atlas    | Render     |
| Bootstrap 5    | RESTful API        | Mongoose ODM     |            |

---

## 📁 Folder Structure

geer-intern-ecommerce-project/
├── public/ # Frontend HTML, CSS, JS
│ ├── index.html # Welcome page
│ ├── products.html # Product listing
│ └── cart.html # Cart system
├── server.js # Express server
├── .env # MongoDB secret
├── package.json # Backend config
└── README.md # You’re reading it 😄

---

## 🔧 Setup Instructions (Local)

### 1. Clone the Repository

```bash
git clone https://github.com/charuchaudhary13/geer-intern-ecommerce-project.git
cd geer-intern-ecommerce-project
2. Create .env File
Add your MongoDB URI in .env:

MONGO_URI=your_mongodb_atlas_connection_string
3. Install Dependencies & Run

npm install
node server.js
Visit: http://localhost:5000

🛠 API Endpoints
Method	Endpoint	Description
GET	/api/products	Fetch all products
GET	/api/products/:id	Fetch single product
POST	/api/products	Add new product
DELETE	/api/products/:id	Delete product

🧑‍💻 Author
charu chaudhary
🔗 LinkedIn : https://www.linkedin.com/in/charu-chaudhary-794727369

"This was a wonderful learning experience building a fully deployed fullstack app from scratch!"

📣 Acknowledgements
🙌 Inspired by Geer.in

🏁 Final Words
This project demonstrates real-world fullstack skills including:

Building REST APIs

Handling MongoDB with Mongoose

Frontend interaction with APIs

Styling with Bootstrap

Full deployment using Render

