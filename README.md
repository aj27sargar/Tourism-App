# 🌍 Tourism App

A full-stack Tourism Web App built with the **MERN stack (MongoDB, Express.js, React.js, Node.js)** to help users discover popular destinations and travel-related content with a smooth, responsive UI.  
Deployed on **Vercel** for frontend and **Render/Node environment** (if applicable) for backend.

### 🔗 Live Link:
👉 [https://tourism-app-flame.vercel.app](https://tourism-app-flame.vercel.app)

---

## ✨ Features

- 🗺️ Browse top-rated destinations
- 📸 View images and brief descriptions
- 🔍 Search places by name
- 📲 Responsive UI for mobile and desktop
- ⚙️ MERN architecture with API routing
- 📦 Backend powered by Express and MongoDB
- 🧾 Clean modular folder structure

---

## 🛠️ Tech Stack

| Frontend       | Backend          | Database | Hosting       |
|----------------|------------------|----------|----------------|
| React.js       | Node.js, Express | MongoDB  | Vercel (frontend) <br> Render/Local/Cloud (backend) |

---

## 📁 Folder Structure (Simplified)

```

tourism-app/
├── frontend/                  # React frontend
│   ├── public/
│   └── src/
│       ├── components/
│       ├── pages/
│       └── App.js
├── backend/                  # Node + Express backend
│   ├── routes/
│   ├── models/
│   ├── controllers/
│   └── server.js
└── .env

````

---

## 🚀 Getting Started (Local Setup)

### 1. Clone the repository
```bash
git clone https://github.com/aj27sargar/tourism-app.git
cd tourism-app
````

### 2. Install dependencies

```bash
# Install frontend
cd frontend
npm install

# Install backend
cd ../backend
npm install
```

### 3. Set up environment variables

Create a `.env` file in the `server` folder:

```
MONGO_URI=your_mongodb_connection_string
PORT=5000
```

### 4. Run the app

```bash
# Run backend
cd backend
npm start

# Run frontend
cd ../frontend
npm start
```

---

## 📷 UI Preview

> ![Homepage Screenshot](https://tourism-app-flame.vercel.app/some-preview.png)
> <img width="1872" height="738" alt="Screenshot 2024-10-18 194338" src="https://github.com/user-attachments/assets/fb898daf-7ca4-411d-b7e8-8c63c535a65e" />


---

## 🙋‍♂️ Author

* **Ajit Sargar**
* [GitHub](https://github.com/aj27sargar)
* [LinkedIn](https://www.linkedin.com/in/ajit-sargar-495a1a253/)

---

## 📜 License

This project is licensed under the MIT License – feel free to use it for learning or building your own tourism projects!

```

