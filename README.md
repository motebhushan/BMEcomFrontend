# 🛒 BM E-Commerce Website (Frontend)

A **full-stack E-Commerce web application** developed using **React** for the frontend and **Spring Boot** for the backend.  
This repository contains the **frontend** codebase built with **React** and **Tailwind CSS**.

---

## 🔥 Features

- 🧑‍💻 User Registration & Login (JWT-based)
- 🛍️ Product Listing with real-time updates
- 🛒 Cart Management
- 📥 Order Placement (Checkout)
- 🧭 Landing Page
- ✉️ Contact Us Page
- 📇 Sign In / Sign Up Forms
- 📊 Admin Dashboard (In Progress)

---

## 🛠 Tech Stack

- **Frontend**: React, Tailwind CSS, Axios, React Router
- **Backend**: Spring Boot, Spring Security, JPA/Hibernate, REST APIs
- **Database**: MySQL
- **Authentication**: JWT (JSON Web Tokens)
- **Tools**: Git, Postman, Maven

---

## 📁 Project Structure

```
BM-Ecom/
├── frontend/      # React App (this repo)
├── backend/       # Spring Boot App (see backend repo)
```

👉 Backend Repository: [bm-ecom (Spring Boot)](https://github.com/motebhushan/bm-ecom)

---

## 🚀 Getting Started

### 1. Clone the Frontend Repository

```bash
git clone https://github.com/motebhushan/BMEcomFrontend.git
cd BMEcomFrontend
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Start Development Server

```bash
npm start
```

The app will run on [http://localhost:3000](http://localhost:3000)

---

## 🔌 Connect to Backend

Ensure your frontend is connected to the backend by updating the API URLs in your Axios services to:

```
http://localhost:8080/api/
```

---

## 🧾 Available Pages

| Page Name        | Description                         |
|------------------|-------------------------------------|
| Landing Page     | Homepage with intro, CTA, features |
| Sign In / Sign Up| User authentication screens        |
| Products Page    | Browse products with details       |
| Cart Page        | View & manage selected products    |
| Checkout         | Place an order (payment: WIP)      |
| Contact Us       | User queries or feedback form      |
| Admin Dashboard  | Product control & analytics (WIP)  |

---

## 🖼️ Screenshots

> Here's a glimpse of the UI:

| Landing Page | Sign In Page | Product Listing |
|--------------|--------------|------------------|
| ![Landing](https://github.com/motebhushan/BMEcomFrontend/blob/main/Screenshots/landingPage.png) | ![SignIn](https://github.com/motebhushan/BMEcomFrontend/blob/main/Screenshots/signIn.png) | ![Products](https://github.com/motebhushan/BMEcomFrontend/blob/main/Screenshots/Products.png) |

| Cart Page | Contact Us Page |
|-----------|------------------|
| ![Cart](https://github.com/motebhushan/BMEcomFrontend/blob/main/Screenshots/Cart.png) | ![Contact](https://github.com/motebhushan/BMEcomFrontend/blob/main/Screenshots/Contact.png) |

> *(Images are stored in the `/screenshots/` folder of this repository)*

---

## 📚 Backend Setup

To set up and run the Spring Boot backend, refer to the instructions provided in the [bm-ecom backend repository](https://github.com/motebhushan/bm-ecom).

---

## 👨‍💻 Developed by

**Bhushan Mote**  
📅 *June 2025 | Full-Stack Web Application*

---

## 📌 Notes

- This project showcases a complete MERN-style architecture using React and Spring Boot.
- More features like payment gateway integration and full admin control are planned in future updates.
