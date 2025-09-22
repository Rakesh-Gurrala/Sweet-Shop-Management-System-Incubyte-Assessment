# Sweet-Shop-Management-System
📷 Screenshots

![Navbar-Section](https://github.com/user-attachments/assets/1984311e-ed88-4712-9723-8315d1c051ce)
![Menu-Section](https://github.com/user-attachments/assets/3f5ee6d3-8304-48e6-9149-53bfdf6c2dff)
![Items-1](https://github.com/user-attachments/assets/27d203d7-9003-4eaa-b0e7-d0f7a06fd3c1)
![Items-2](https://github.com/user-attachments/assets/4253bdd0-23c6-4fa0-8ee7-48596861fe89)
![Item-3](https://github.com/user-attachments/assets/147a8ea8-358f-4b57-9098-1cbd022f68e3)
![Item-4](https://github.com/user-attachments/assets/02d68c04-2029-43a7-9180-3a89d1539568)
![app-store](https://github.com/user-attachments/assets/c48ff3b7-d471-4acd-8346-060d419e0422)
![contact](https://github.com/user-attachments/assets/b4d12fbe-7193-4dce-8cdb-9b268267f136)
![Items-list](https://github.com/user-attachments/assets/f5126a75-b548-4d16-afc1-94fbb89005c3)
![Items-list-2](https://github.com/user-attachments/assets/df31d83f-fe57-40e7-b987-d6e31f81c554)
![delivery](https://github.com/user-attachments/assets/e6a5e184-9a78-4470-96dd-2b2c5ab672c0)
![admin](https://github.com/user-attachments/assets/e7fd026d-0a19-4136-b898-429d2673c731)
![login](https://github.com/user-attachments/assets/c19f1dac-275e-4262-8a4f-88fb4694cae8)
![sign](https://github.com/user-attachments/assets/8b2c6e9c-cd53-479a-b9b2-334918841707)

A modern **Sweet Shop Management System** built with **React (Vite)** for the frontend.  
This project is part of the **Incubyte Assessment** and demonstrates a full-featured web application with a clean UI, product management, cart, and order placement functionality.

---

## 🗂️ Project Structure

Sweet-Shop-Management-System/
├── Admin/ # Admin panel (future backend integration)
├── Backend/ # Backend folder (API / server logic)
├── Frontend/ # React frontend application
│ ├── public/ # Static assets (images, icons)
│ ├── src/ # React source code
│ │ ├── components/ # Reusable components (Navbar, Footer, SweetItem, etc.)
│ │ ├── context/ # Context API for state management
│ │ ├── pages/ # Main pages (Home, Cart, PlaceOrder)
│ │ ├── App.jsx # Root component
│ │ └── main.jsx # React DOM entry point
│ ├── package.json
│ └── vite.config.js
├── .gitignore
└── README.md

yaml
Copy code

---

## 💻 Features

- Browse and explore a variety of sweets.
- Add items to cart and place orders.
- Responsive UI for desktop and mobile.
- Context API for state management.
- Admin and Backend folders included for future integration.
- Static frontend deployable via **GitHub Pages**.

---

## 🚀 Installation (Frontend)

1. Clone the repository:

```bash
git clone https://github.com/YourUsername/Sweet-Shop-Management-System.git
cd Sweet-Shop-Management-System/Frontend
Install dependencies:

bash
Copy code
npm install
Start the development server:

bash
Copy code
npm run dev
Open http://localhost:5173 in your browser to view the app.

📦 Deployment (GitHub Pages)
Install gh-pages package:

bash
Copy code
npm install gh-pages --save-dev
Add the following to package.json:

json
Copy code
"homepage": "https://YourUsername.github.io/Sweet-Shop-Management-System/",
"scripts": {
  "predeploy": "npm run build",
  "deploy": "gh-pages -d dist"
}
Deploy:

bash
Copy code
npm run deploy
Your frontend will be live at:

cpp
Copy code
https://YourUsername.github.io/Sweet-Shop-Management-System/
⚠️ Notes
GitHub Pages only hosts the frontend (/Frontend).

Backend (/Backend) and Admin (/Admin) are included for future integration but are not live on GitHub Pages.

Make sure your index.html exists in the dist/ folder after building for GitHub Pages.

👨‍💻 Author
Rakesh Gurrala
GitHub: https://github.com/Rakesh-Gurrala














