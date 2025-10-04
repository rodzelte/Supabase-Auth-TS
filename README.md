# 🚀 Supabase-Auth-TS

A modern authentication starter built with **Supabase**, **React (Vite)**, **TypeScript**, and **TailwindCSS**.  
Perfect for quickly bootstrapping secure, full-stack web apps with email/password or OAuth login.

---

## 🧩 Tech Stack

| Tool                                          | Purpose                               |
| --------------------------------------------- | ------------------------------------- |
| [Supabase](https://supabase.com)              | Authentication, Database, and API     |
| [React](https://react.dev/)                   | Frontend Framework                    |
| [Vite](https://vitejs.dev/)                   | Lightning-fast Development Build Tool |
| [TypeScript](https://www.typescriptlang.org/) | Type Safety and Autocomplete          |
| [TailwindCSS](https://tailwindcss.com/)       | Utility-first Styling                 |

---

## 📦 Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/rodzelte/Supabase-Auth-TS.git
cd Supabase-Auth-TS

2️⃣ Install Dependencies
npm install


3️⃣ Set Up Supabase

Go to Supabase Dashboard
.

Create a new project.

Go to Project Settings → API and copy your:

SUPABASE_URL

SUPABASE_ANON_KEY

4️⃣ Create an .env file
VITE_SUPABASE_URL=https://your-project-id.supabase.co
VITE_SUPABASE_ANON_KEY=your-anon-key

💻 Development

To start the dev server:

npm run dev


Then open:
👉 http://localhost:5173

🔐 Authentication Features

✅ Email + Password Signup / Login
✅ OAuth Providers (Google, GitHub, etc.)
✅ Persistent Sessions
✅ Realtime Auth State Management

🧠 Project Structure
Supabase-Auth-TS/
├── src/
│   ├── components/
│   ├── pages/
│   ├── hooks/
│   ├── lib/
│   │   └── supabaseClient.ts   # Supabase initialization
│   ├── App.tsx
│   └── main.tsx
├── public/
├── .env.example
├── index.html
├── tailwind.config.js
├── tsconfig.json
└── vite.config.ts

🌍 Deployment

You can deploy easily with Vercel
 or Netlify
:

Deploy to Vercel
npm run build
vercel deploy

🧑‍💻 Author

Rodzel John Te
💼 GitHub: @rodzelte

⭐ License

This project is open-source under the MIT License.

---

```
