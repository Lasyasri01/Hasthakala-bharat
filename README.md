# Hasthakala-bharat
🌸 Hasthakala Bharat – Vibrant Crafts of India

Hasthakala Bharat is a full-stack web application developed as part of my learning project.
It highlights the diversity of Indian handicrafts and provides features like craft browsing, customer reviews, and user authentication.
The project uses a modern stack with React (Vite + TypeScript) for the frontend and Express + SQLite for the backend.

---

🚀 Features

* 🛍️ Browse crafts by category and subcategory
* ✍️ Add and view customer reviews (Name, Email, Phone, Comment, Rating)
* 🔐 User login & account creation
* 📊 Basic craft categorization and browsing

---

## 🛠️ Tech Stack

* Frontend: React + Vite + TypeScript + TailwindCSS
* Backend: Node.js + Express.js + SQLite3
* Database: SQLite (with `database.js`)

---

## 📂 Project Structure

```
hasthakala-bharat/
│── .dockerignore
│── .gitignore
│── bun.lockb
│── components.json
│── docker-compose.yml
│── eslint.config.js
│── index.html
│── package.json
│── package-lock.json
│── postcss.config.js
│── tailwind.config.ts
│── tsconfig.json
│── tsconfig.app.json
│── tsconfig.node.json
│── vite.config.ts
│
├── public/                  # Static assets
│   ├── custom.ico
│   ├── images/
│   │   └── boy-placard.png
│   ├── placeholder.svg
│   └── robots.txt
│
├── src/                     # Frontend (React + TSX)
│   ├── App.tsx
│   ├── App.css
│   ├── main.tsx
│   ├── index.css
│   ├── vite-env.d.ts
│   │
│   ├── components/          # Reusable components
│   │   ├── ChatBot.tsx
│   │   ├── Footer.tsx
│   │   ├── Navigation.tsx
│   │   ├── ReviewForm.tsx
│   │   ├── ReviewList.tsx
│   │   └── ui/              # Shadcn UI components
│   │
│   ├── pages/               # Page-level components
│   │   ├── Homepage.tsx
│   │   ├── AboutUs.tsx
│   │   ├── BuyProducts.tsx
│   │   ├── CraftCategory.tsx
│   │   ├── CraftWorkshops.tsx
│   │   ├── CreateAccount.tsx
│   │   ├── Login.tsx
│   │   ├── Reviews.tsx
│   │   ├── SubCategoryDetail.tsx
│   │   └── NotFound.tsx
│   │
│   ├── data/                # Static data
│   │   ├── craftsData.ts
│   │   └── etsyProducts.ts
│   │
│   ├── hooks/               # Custom hooks
│   │   ├── use-mobile.tsx
│   │   └── use-toast.ts
│   │
│   └── lib/                 # Utilities
│       └── utils.ts
│
└── hasthakala-server/       # Backend (Express + SQLite)
    ├── .dockerignore
    ├── .env
    ├── Dockerfile
    ├── database.js
    ├── fix-db.js
    ├── hasthakala.db
    ├── package.json
    ├── package-lock.json
    ├── server.js
    │
    ├── routes/              # Backend API routes
    │   ├── chat.js
    │   └── reviews.js
    │
    └── uploads/             # Uploaded images
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repo

```bash
git clone https://github.com/Lasyasri01/Hasthakala-bharat.git
cd Hasthakala-bharat
```

### 2️⃣ Install dependencies

Frontend:

```bash
npm install
```

Backend:

```bash
cd hasthakala-server
npm install
```

### 3️⃣ Run locally

Start backend:

```bash
cd hasthakala-server
node server.js
```

Start frontend:

```bash
npm run dev
```

👉 Frontend runs on `http://localhost:5173`
👉 Backend runs on `http://localhost:5050`

---

## 🔮 Future Enhancements

* Payment gateway integration
* Multi-language support
* Live artisan workshop booking
