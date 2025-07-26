# 📘 Blogify – A Simple Blogging Platform

**Blogify** is a Node.js-based blogging application using Express, MongoDB, and EJS templating. It allows users to register, log in, create blog posts, upload images, and leave comments. The app is structured for clarity and ease of extension, following modular coding principles.

## 🚀 Features

- User authentication (signup/signin)
- Create, read, and delete blog posts
- Upload images for each post
- Add comments to blogs
- EJS-based templating with reusable components


blogify/
├── app.js # Main server file
├── package.json # Project metadata and dependencies
├── middlewares/ # Authentication middleware
├── models/ # Mongoose models (User, Blog, Comment)
├── public/ # Static files (images, uploads)
├── routes/ # Express route handlers
├── services/ # Business logic for authentication
├── views/ # EJS views and partial templates


Install dependencies
npm install

Start the server
node app.js

Visit the app
http://localhost:3000


Dependencies
Node.js

Express.js

MongoDB

Mongoose

EJS

Multer (for file uploads)



