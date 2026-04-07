# 🛒 Full-Stack E-Commerce Platform

![License](https://img.shields.io/github/license/ShreyashMishra10/E-commerce-project)
![Stars](https://img.shields.io/github/stars/ShreyashMishra10/E-commerce-project)
![Issues](https://img.shields.io/github/issues/ShreyashMishra10/E-commerce-project)

A high-performance, full-stack e-commerce application built using the **MERN** stack. This project focuses on a seamless user experience, scalable database architecture, and a modern UI/UX.

---

## 🚀 Key Features

* **Secure Authentication:** User login and registration using JWT (JSON Web Tokens).
* **Product Catalog:** Dynamic browsing with real-time search and filtering.
* **Persistent Shopping Cart:** Items remain in the cart even after page refresh.
* **Responsive Design:** Optimized for mobile, tablet, and desktop views.
* **State Management:** Robust data handling using React Hooks and Context API.
* **Clean Architecture:** Separation of concerns between the Frontend (React) and Backend (Node/Express).

---

## 🛠️ Tech Stack

**Frontend:**
* React.js
* JavaScript (ES6+)
* Tailwind CSS / CSS3
* Pnpm (Package Manager)

**Backend:**
* Node.js
* Express.js
* MongoDB
* Mongoose / Drizzle ORM

---

## 📁 Project Structure

```text
├── client/                # React Frontend
│   ├── src/
│   │   ├── components/    # Reusable UI elements
│   │   ├── pages/         # View components (Home, Product, Cart)
│   │   └── context/       # Global state management
├── server/                # Node.js Backend API
│   ├── models/            # Database Schemas
│   ├── routes/            # API Endpoints
│   └── controllers/       # Business Logic & Request Handling
└── README.md
```

## ⚙️ Installation & Setup

This project uses **npm** for faster and more efficient dependency management.

### 1. Clone the Repository
```bash
git clone "https://github.com/ShreyashMishra10/E-commerce-project.git"
```

### 2. Setup Backend
```Bash
cd server
npm install
```

### 3. Setup Frontend
```Bash
cd ../client
npm install
```

### 4. Run the Application
Open two terminals to run both concurrently:

Terminal 1 (Backend):

```Bash
cd server
npm start
```
Terminal 2 (Frontend):

```Bash
cd client
npm dev
```
### 👤 Author
Shreyash Mishra

**GitHub: @ShreyashMishra10**  
**Role: Full-Stack Developer | Final Year CS Student**
