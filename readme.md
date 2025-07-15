# 🌐 URL Shortener REST API

A full-stack URL Shortener service built with **Node.js**, **Express**, and **MongoDB**. This project allows users to shorten long URLs into compact links and redirect them using the shortened URLs. Includes a minimal front-end for quick usage and testing.

---

## 📖 Table of Contents
- [✨ Features](#-features)
- [📸 Screenshots](#-screenshots)
- [🚀 Tech Stack](#-tech-stack)
- [📂 Project Structure](#-project-structure)
- [📥 API Endpoints](#-api-endpoints)
- [🛠️ Local Setup](#-local-setup)
- [🌐 Deployment](#-deployment)
- [🤝 Contributing](#-contributing)
- [📜 License](#-license)

---

## ✨ Features

✅ Shortens long URLs into compact, shareable links  
✅ Redirects short URLs to their original destinations  
✅ Validates URLs before shortening  
✅ Simple and responsive front-end UI included  
✅ REST API tested with Postman  
✅ MongoDB integration for persistent storage  
✅ Lightweight and easy to deploy  

---

## 📸 Screenshots

### 🔗 Frontend Interface
![Frontend UI](screenshots/frontend.png)

### 📬 API Tested in Postman
![Postman Screenshot](screenshots/postman.png)

---

## 🚀 Tech Stack

- **Backend:** Node.js, Express.js
- **Database:** MongoDB (with Mongoose ODM)
- **Frontend:** HTML, CSS, jQuery (for API interaction)
- **Other Packages:**
  - `config`: Environment management
  - `shortid`: Generate unique short URL codes
  - `valid-url`: Validate URLs
- **Dev Tools:** Postman, Git, Nodemon

---

## 📂 Project Structure

📦url-shortener
┣ 📂config
┃ ┗ default.json
┣ 📂models
┃ ┗ URL.js
┣ 📂routes
┃ ┣ index.js
┃ ┗ url.js
┣ 📜index.js
┣ 📜index.html
┣ 📜package.json
┣ 📜README.md

## 🛠️ Local Setup
### 1️⃣ Clone the Repository

git clone https://github.com/Yogeshkharb111/url-shortener.git

cd url-shortener
### 2️⃣ Install Dependencies

npm install
### 3️⃣ Configure MongoDB
Update the config/default.json file with your MongoDB URI:

{
  "mongoURI": "your-mongodb-uri-here",
  "baseURL": "http://localhost:5000"
}
### 4️⃣ Run the Application

npm run dev
Visit http://localhost:5000 in your browser.