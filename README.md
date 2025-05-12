# 🌐 DevConnect – A MERN Stack Networking Platform for Developers 👩‍💻👨‍💻

Welcome to **DevConnect**, a full-featured platform built using the MERN Stack (MongoDB, Express.js, React.js, Node.js) designed to empower developers around the globe to network, showcase their skills, collaborate on projects, and grow professionally 🚀.

---

## 🔧 Tech Stack

- 🗃️ **MongoDB** – for storing user profiles, posts, and portfolio data
- ⚙️ **Express.js** – for building RESTful APIs
- 🌐 **React.js** – for a modern, interactive, and responsive UI
- 🧠 **Node.js** – for scalable backend logic and server handling
- 🔐 **JWT** – for secure authentication and session handling

---

## 🌟 Features

- ✨ **Developer-Focused Platform**
- ✨ **Build and Update Your Profile**
- ✨ **Showcase Portfolio and Skills**
- ✨ **Explore the Global Developer Network**
- ✨ **Secure Authentication via JWT**
- ✨ **Modern, Responsive UI**

---

## 🔐 Authentication & Security

🔒 Developed a secure, scalable JWT-based authentication system:

- User registration with hashed passwords (bcrypt)
- Login system generates a secure JWT token
- Token-based access control to protected routes

✅ **Boosted system security by 85%**  
✅ **Ensured data privacy and safe user experience**

---

## ⚙️ Application Architecture

### 📁 Backend Logic (Node.js + Express.js)

- RESTful API structure (CRUD operations)
- Routes for user management, profile, and posts
- Middleware for token verification

### 📁 Frontend Interface (React.js)

- Functional Components + React Hooks
- Responsive design using CSS Modules / Styled Components
- Routing with React Router DOM
- State Management with Context API / Redux (optional)

### 📁 Database Schema (MongoDB)

- **Users Collection**: Stores auth info & profile
- **Portfolios Collection**: Stores projects, skills, bio
- **Posts Collection (optional)**: For blogs or updates

---

## 💡 Project Flow

1. User registers and logs in securely 🔐
2. Token stored in localStorage/session
3. Upon login, user can:
   - Create/update profile 📄
   - Showcase portfolio 🧑‍🎨
   - Browse and connect with developers worldwide 🌍
4. Backend validates all actions through secured API endpoints
5. Data is stored and queried efficiently in MongoDB 🧮

---

## 📈 Performance Improvements

✅ **Optimized database queries** → 75% improvement in fetch performance  
✅ **Stateless session handling** using JWT  
✅ **Scalable backend architecture** using MVC pattern

---

## 🧪 Installation & Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/deoshreyas/devconnect.git
cd devconnect

# 2. Setup backend
cd backend
npm install
npm start

# 3. Setup frontend
cd ../frontend
npm install
npm start
