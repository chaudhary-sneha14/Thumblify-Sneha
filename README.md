🎨 Thumblify – AI Thumbnail Generator

Thumblify is an AI-powered web application that generates high-quality thumbnails instantly.
Simply describe your idea, select a style, and let AI create visually engaging thumbnails for your content.

Built using the MERN Stack with modern UI design and AI image generation capabilities.

🚀 Overview

Thumblify helps YouTubers, marketers, and content creators create professional thumbnails without needing design skills or editing software.

✅ Describe your idea
✅ Choose style & aspect ratio
✅ Generate stunning thumbnails in seconds

🌐 Live Demo & Repository

🔗 Live Demo: Thumblify
🔗 GitHub Repository:
https://github.com/Sumit444-commits/Thumblify

📸 Application Preview
🏠 Home Page
<img width="1893" height="871" alt="Home Page" src="https://github.com/user-attachments/assets/ef692f1b-cc51-4a1e-a89c-bb674726c24a" />
🎯 Generator Page
<img width="1201" height="688" alt="Generator Page" src="https://github.com/user-attachments/assets/c13800cf-fba6-4ff4-978c-2954506bce93" />
🖼️ My Generations
<img width="1221" height="677" alt="My Generations Page" src="https://github.com/user-attachments/assets/96951d90-0c23-460e-b4d1-e58dfa47118a" />
✨ Features

🎨 AI Thumbnail Generation
Generate thumbnails using natural language prompts.

🧩 Custom Styles

Bold & Graphic

Minimalist

Photorealistic

Creative Variants

📐 Multiple Aspect Ratios

YouTube → 16:9

Instagram → 1:1

TikTok / Shorts → 9:16

🎯 Color Schemes
Preset branding palettes for consistent visuals.

🖼️ User Gallery
Access and manage all previously generated thumbnails.

🔐 Secure Authentication
Session-based login system.

⚡ Fast & Responsive UI
Optimized using Vite + Tailwind CSS.

🛠️ Tech Stack
🎯 Frontend

React (Vite)

Tailwind CSS

Lucide React Icons

Context API

⚙️ Backend

Node.js

Express.js

MongoDB + Mongoose

Express Session

Zod Validation

🤖 AI & Media

Bytez.js (AI Image Models)

Cloudinary (Image Storage & Delivery)

🚀 Deployment

Vercel (Frontend + Serverless Backend)

📂 Project Structure
Backend
backend/
│
├── controllers/     # Auth & thumbnail logic
├── models/          # MongoDB schemas
├── routes/          # API endpoints
├── middleware/      # Authentication & error handling
├── validate/        # Zod validation schemas
└── index.js
Frontend
frontend/
│
└── src/
    ├── pages/        # Home, Generator, Gallery
    ├── components/   # UI components
    ├── context/      # Global state management
    └── main.jsx
⚙️ Getting Started
✅ Prerequisites

Node.js (v18+)

MongoDB Atlas Account

Bytez API Key

Cloudinary Account

📥 Installation
1️⃣ Clone Repository
git clone <repository-url>
cd thumblify
2️⃣ Install Dependencies
Backend
cd backend
npm install
Frontend
cd ../frontend
npm install
🔐 Environment Variables
Backend .env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
SESSION_KEY=your_secret_key
BYTEZ_API_KEY=your_bytez_api_key
CLOUDINARY_URL=cloudinary://<api_key>:<api_secret>@<cloud_name>
NODE_ENV=production
Frontend .env
VITE_BASE_URI=http://localhost:5000
▶️ Run Locally
Start Backend
cd backend
npm start
Start Frontend
cd frontend
npm run dev
Application Runs On

Frontend → http://localhost:5173

Backend → http://localhost:5000

🧠 How It Works

User enters thumbnail idea

Prompt sent to Bytez AI

AI generates image

Image uploaded to Cloudinary

Metadata stored in MongoDB

Thumbnail displayed in user gallery

👩‍💻 Author

Sneha Chaudhary
Full Stack Developer | MERN Stack Enthusiast

⭐ Support

If you found this project useful:

⭐ Star the repository
🍴 Fork and contribute
💡 Share feedback
