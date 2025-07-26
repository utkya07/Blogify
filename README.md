# 📝 Blogify – A Simple Blogging Platform

**Blogify** is a full-stack blogging application built using **Node.js**, **Express**, **MongoDB**, and **EJS** templating. It allows users to register, log in, create and view blogs, upload images, and comment on posts. The codebase is clean, modular, and suitable for learning or extending into a full-featured content platform.

## ✨ Features

- 🔐 User authentication (Sign up / Sign in)
- 📝 Create, view, and delete blog posts
- 🖼️ Image upload support via Multer
- 💬 Commenting system on blogs
- 🖥️ Server-rendered views using EJS templates
- 📁 Organized structure for scalability

## 🧾 Project Structure

```

blogify/
├── app.js                  # Main application entry point
├── package.json            # Project dependencies and scripts
├── middlewares/            # Auth middleware
├── models/                 # Mongoose models for Blog, User, Comment
├── public/                 # Static assets (uploads, images)
├── routes/                 # Route handlers for blog and user logic
├── services/               # Business logic (e.g., authentication service)
├── views/                  # EJS templates and UI partials
└── uploads/                # Uploaded images via Multer

````

## 🚀 Getting Started

### Prerequisites

- Node.js installed (v14+ recommended)
- MongoDB instance (local or cloud)

### Installation

```bash
git clone https://github.com/your-username/blogify.git
cd blogify
npm install
````

### Running the Application

```bash
node app.js
```

Open your browser and visit:

```
http://localhost:3000
```

## 📦 Dependencies

* express
* mongoose
* multer
* ejs
* bcrypt
* express-session
* dotenv (if environment variables are configured)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

> Built with 💻 using Node.js, Express & MongoDB

```

---
