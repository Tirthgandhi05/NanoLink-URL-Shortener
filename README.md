<div align="center">
  <img src="https://raw.githubusercontent.com/Tirthgandhi05/NanoLink-URL-Shortener/main/link-logo.png" alt="NanoLink Logo" width="150">
  <h1 align="center">NanoLink - URL Shortener 🚀</h1>
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js Badge">
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js Badge">
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB Badge">
  <img src="https://img.shields.io/badge/EJS-B4CA65?style=for-the-badge&logo=ejs&logoColor=black" alt="EJS Badge">
</p>

### This is a full-stack URL shortening web application built using Node.js, Express, and MongoDB. It provides a clean user interface to create and manage short links, and tracks usage analytics like click counts.

---

## 📋 Prerequisites

Before you begin, ensure you have the following installed on your system:
* **Node.js** (v14 or later recommended)
* **npm** (Node Package Manager)
* **MongoDB** (Ensure the database server is running)

---

## ✨ Features Offered:

-   ### *Shorten New URL:*
    Users can easily shorten any valid URL using the simple form on the homepage. The application generates a unique 8-character ID for each link.

-   ### *Fast Redirection:*
    Visiting a generated NanoLink instantly and reliably redirects the user to the original long URL. This ensures a smooth experience for anyone using the short link.

-   ### *Display All Links & Analytics:*
    The homepage features a clean, modern table that displays all the links created. This table includes the short ID, the original destination URL, and a live counter for the number of clicks.

-   ### *Click Counter:*
    Track the popularity of your links! The application logs every visit to a short URL and displays the total click count in the main table, giving you insight into how often your links are being used.

---

## 🛠️ Tech Stack

-   **Backend:** Node.js, Express.js
-   **Database:** MongoDB with Mongoose
-   **Frontend:** EJS for Server-Side Rendering
-   **ID Generation:** `shortid` for fast and secure unique ID generation
-   **Environment Variables:** `dotenv` for managing secrets

---

## 🚀 Getting Started

Follow these steps to get a local copy of the project up and running.

1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/Tirthgandhi05/NanoLink-URL-Shortener.git]
    ```

2.  **Navigate to the Project Directory**
    ```bash
    cd NanoLink-URL-Shortener
    ```

3.  **Install Dependencies**
    ```bash
    npm install
    ```

4.  **Create an Environment File**
    Create a `.env` file in the root of the project and add your MongoDB connection string.
    ```
    MONGODB_URL="mongodb://127.0.0.1:27017/shorturl"
    ```

5.  **Start the Server**
    ```bash
    npm start
    ```
    The application will be running at `http://localhost:8000`.
