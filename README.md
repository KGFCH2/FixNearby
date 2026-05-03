<div align="center">
  <h1 align="center">FixNearby 🛠️</h1>
  <p align="center">
    <strong>An open-source hyperlocal service platform connecting users with nearby workers.</strong>
  </p>
  <p align="center">
    <a href="https://github.com/souma9830/FixNearby/issues"><img alt="Issues" src="https://img.shields.io/github/issues/souma9830/FixNearby?color=blue&style=flat-square" /></a>
    <a href="https://github.com/souma9830/FixNearby/pulls"><img alt="Pull Requests" src="https://img.shields.io/github/issues-pr/souma9830/FixNearby?color=green&style=flat-square" /></a>
    <a href="https://github.com/souma9830/FixNearby/blob/master/LICENSE"><img alt="License" src="https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square" /></a>
  </p>
</div>

---

## 📖 What We Are Building

**FixNearby** is designed to bridge the gap between people who need everyday services (like plumbing, electrical work, carpentry, or cleaning) and the skilled professionals who provide them in their local neighborhoods. 

Unlike massive corporate directories, FixNearby aims to be a lightweight, fast, and community-driven application built entirely on the **MERN Stack** (MongoDB, Express, React, Node.js) and styled with **Tailwind CSS**.

## 🏗️ Current Project State

This repository is currently a **scaffolded starter template**. We have built about 50% of the foundational architecture so that open-source contributors can easily jump in and start coding features immediately!

### What's already built:
- **Frontend (`client/`)**: A Vite + React application with React Router configured. It includes a fully responsive Tailwind CSS landing page, navigation, and dummy-data placeholder pages (`/services`, `/worker/:id`, `/bookings`, `/profile`).
- **Backend (`server/`)**: An Express.js server connected to MongoDB. It includes a basic project folder structure (`routes`, `controllers`, `models`, `middleware`), a basic `User` schema with password hashing, and a JWT authentication skeleton.

## 🎯 What We Need (The Roadmap)

We rely on the open-source community to bring this platform to life! If you are looking to contribute, here are the core features we need help building right now:

### 🚀 Frontend Tasks (React)
- **API Integration**: Connect the dummy UI forms (Login, Register, Profile) to the actual backend endpoints.
- **State Management**: Implement Context API or Redux to manage the user's authentication state globally.
- **Search & Filtering**: Build the logic on the `/services` page to filter workers by category, rating, and location.
- **Interactive Dashboards**: Replace the placeholder `/dashboard` and `/bookings` pages with real dynamic data tables.

### ⚙️ Backend Tasks (Node.js)
- **Authentication**: Finish the JWT login/register flow in `authController.js` and enforce protected routes.
- **Database Models**: Create new Mongoose schemas for `Worker` profiles, `Services`, `Bookings`, and `Reviews`.
- **RESTful APIs**: Build CRUD endpoints for fetching nearby workers, submitting reviews, and managing user bookings.
- **Validation**: Add robust input validation and error handling using a library like Joi or Express-Validator.

> **Tip:** Search the codebase for `TODO:` comments. We've left dozens of hints exactly where new code needs to be added!

---

## 💻 Tech Stack

- **Frontend:** React.js (Vite), React Router v6, Tailwind CSS
- **Backend:** Node.js, Express.js, JSON Web Tokens (JWT), Bcrypt
- **Database:** MongoDB, Mongoose

---

## 🛠️ Getting Started

Want to run the project locally? Follow these steps.

### Prerequisites
- Node.js (v18+ recommended)
- MongoDB (Local instance or MongoDB Atlas)

### Backend Setup
1. Navigate to the server folder: 
   ```bash
   cd server
   ```
2. Install dependencies: 
   ```bash
   npm install
   ```
3. Copy `.env.example` to `.env` in the server root and fill in your details (like `MONGODB_URI` and `JWT_SECRET`).
4. Start the server: 
   ```bash
   npm run dev
   ```

### Frontend Setup
1. Navigate to the client folder in a new terminal: 
   ```bash
   cd client
   ```
2. Install dependencies: 
   ```bash
   npm install
   ```
3. Start the dev server: 
   ```bash
   npm run dev
   ```

---

## 🤝 How to Contribute

We welcome contributions from everyone—whether you are a beginner looking for your first PR, or a senior dev wanting to design system architecture.

Please read our [**CONTRIBUTING.md**](./CONTRIBUTING.md) for detailed instructions on how to fork the repo, create a branch, and submit a Pull Request.

## 📜 License
This project is open-source and available under the [MIT License](LICENSE).
