# React-Supabase

A modern **React + Supabase** CRUD scaffolded with **Vite**, styled using **Tailwind CSS**, and powered by **ShadCN UI**, **Lucide Icons**, and **Zustand** for state management.
It comes with a clean, professional folder structure for scalability.

---

## 📂 Project Structure

```
├─ public/
├─ src/
│  ├─ api/
│  ├─ assets/
│  ├─ components/
│  │  ├─ chat/
│  │  ├─ header/
│  │  ├─ todo/
│  │  └─ ui/
│  ├─ hooks/
│  ├─ lib/
│  ├─ pages/
│  ├─ store/
│  ├─ utils/
│  ├─ App.jsx
│  ├─ index.css
│  └─ main.jsx
├─ .gitignore
├─ components.json
├─ eslint.config.js
├─ index.html
├─ package-lock.json
├─ package.json
├─ README.md
├─ tsconfig.app.json
├─ tsconfig.json
├─ tsconfig.node.json
└─ vite.config.js
```

---

## ⚡ Features

-   🔥 Full CRUD functionality with Supabase backend
-   🎨 UI built with TailwindCSS + ShadCN components
-   🌓 Dark mode support via custom hook (`useDarkMode`)
-   🗂 Organized, scalable folder structure
-   ✔ Zustand for state management
-   💬 Realtime chat functionality with Supabase

---

## 🚀 Getting Started

### 1. Clone & Install

```bash
git clone https://github.com/thealihamza04/React-SB.git
cd React-SB
npm install
```

### 2. Configure Supabase

Create a `.env` file in the root:

```env
VITE_SUPABASE_URL=your_supabase_url        # Settings → API → Project URL
VITE_SUPABASE_ANON_KEY=your_anon_key      # Settings → API Keys → anon/public key
```

### 3. Run Development Server

```bash
npm run dev
```

Visit [http://localhost:5173](http://localhost:5173)

---

## 💬 Realtime Chat

The application now includes a realtime chat feature, powered by Supabase's realtime capabilities. Users can send and receive messages in real time. The chat component is located in `src/components/chat/`.

---

## 🛠 Tech Stack

-   **React 18 + Vite**
-   **Supabase** (Database + Backend)
-   **Zustand** (State Management)
-   **TailwindCSS**
-   **ShadCN UI Components**
-   **Lucide React Icons**

---
