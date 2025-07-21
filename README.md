# MERN + TypeScript + Tailwind Boilerplate

This is a starter template for a full-stack MERN app using:

* **Express (TypeScript)**
* **React (Vite + TypeScript)**
* **Tailwind CSS**

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Install dependencies

```bash
cd backend
npm install

cd ../frontend
npm install
```

### 3. Start the development servers

In two separate terminals, run:

**Backend**

```bash
cd backend
npm run dev
```

**Frontend**

```bash
cd frontend
npm run dev
```

---

## ⚙️ Environment Variables

In the `/backend` directory, create a `.env` file:

```
PORT=3000
DOTENV_CONFIG_QUIET=true # this is only to get rid of the .env log that's outputted in the console (optional)
```

---

## 🔗 Default Ports

* Frontend (Vite): `http://localhost:5174`
* Backend (Express): `http://localhost:3000`

---

## 📦 Tech Stack

* **Backend:** Node.js, Express, TypeScript, dotenv, cookie-parser, bcrypt, JWT
* **Frontend:** React, Vite, TypeScript, Tailwind CSS
