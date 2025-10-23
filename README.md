# 📊 MERN Dashboard Project

A simple, responsive dashboard application built with the **MERN stack (MongoDB, Express.js, React, Node.js)** for managing and visualizing data. It includes interactive charts, tables, and multiple dashboard sections with light and dark themes.

## 🚀 Features
- Interactive dashboard with multiple sections  
- CRUD operations for managing products, customers, and transactions  
- Sales analytics (daily, monthly, breakdown views)  
- Geographical data visualization  
- Light and dark mode support  
- Fully responsive design  

## 💻 Tech Stack
- **Frontend:** React, Material-UI, Nivo Charts, React Router  
- **Backend:** Node.js, Express.js, MongoDB, Mongoose  
- **Other Tools:** Redux Toolkit, dotenv, CORS, Helmet, Morgan  

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd dashboard
   ```

2. Set up the client:
   ```bash
   cd client
   npm install
   npm run dev
   ```

3. Set up the server:
   ```bash
   cd server
   npm install
   npm run dev
   ```

4. Open the app at:
   ```
   http://localhost:5173
   ```

## 🌍 Environment Variables

Create a `.env` file in both the `client` and `server` directories.

**Client (`client/.env`):**
```
VITE_APP_BASE_URL=http://localhost:5001
```

**Server (`server/.env`):**
```
MONGO_URL=your_mongodb_connection_url
PORT=5001
```

> ⚠️ Do not commit `.env` files to version control.

## 🧩 Folder Structure
```
MERN-Dashboard/
├── client/        # React frontend
├── server/        # Express backend
└── README.md
```

## 📈 Live Demo
[Click here to view the demo](https://react-dashboard12.vercel.app)

---

MIT License
