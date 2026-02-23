🎨 Thumblify – AI Thumbnail Generator
Thumblify is a powerful AI-driven web application that generates high quality thumbnails.
Just describe your idea, choose a style, and let AI create eye-catching visuals for your content.

MongoDB Express.js React NodeJS TailwindCSS
<img width="1275" height="686" alt="image" src="https://github.com/user-attachments/assets/75e08d1e-1d62-4b7c-8a3b-06dc7622e68f" />


Perfect for YouTubers, marketers, and content creators who want professional thumbnails without design skills.

Thumbnail
🌐 Live Demo & Repository
🔗 Live Demo: Thumblify


🔗 GitHub Repository: https://github.com/Sumit444-commits/Thumblify

📸 Preview
Home
<img width="1893" height="871" alt="image" src="https://github.com/user-attachments/assets/ef692f1b-cc51-4a1e-a89c-bb674726c24a" />


Generator Page
<img width="1201" height="688" alt="image" src="https://github.com/user-attachments/assets/c13800cf-fba6-4ff4-978c-2954506bce93" />


My Generations Page
<img width="1221" height="677" alt="image" src="https://github.com/user-attachments/assets/96951d90-0c23-460e-b4d1-e58dfa47118a" />


🚀 Features
AI-Powered Generation – Describe your topic and let AI bring it to life.
Customizable Styles – Bold & Graphic, Minimalist, Photorealistic, and more.
Aspect Ratios –
YouTube: 16:9
Instagram: 1:1
TikTok / Shorts: 9:16
Color Schemes – Preset palettes for branding.
User Gallery – View all your past generations.
Secure Authentication – Session-based user accounts.
Fast & Responsive UI – Built with Vite + Tailwind CSS.
🛠️ Tech Stack
Frontend
React (Vite)
Tailwind CSS
Lucide React (Icons)
Backend
Node.js + Express
MongoDB + Mongoose
Express-Session
Bytez.js (AI Models)
Cloudinary (Image hosting)
Zod (Validation)
Deployment
Vercel (Frontend + Serverless Backend)
📂 Project Structure
Backend
backend/ ├── controllers/ # Auth & generation logic

├── models/ # Mongoose schemas

├── routes/ # API routes

├── middleware/ # Auth & error handling

├── validate/ # Zod schemas

└── index.js

Frontend
frontend/

├── src/

│ ├── pages/ # Home, Generator, My Generations

│ ├── components/ # Navbar, Footer, Inputs

│ ├── context/ # Session & global state

│ └── main.jsx

⚙️ Getting Started
Prerequisites
React JS
Node.js v18+
MongoDB Atlas account
Bytez.js API Key
📥 Installation
1. Clone the repository
git clone 

cd thumblify

2. Install dependencies
## Backend
cd backend
npm install

## Frontend
cd ../frontend
npm install

🔐 Environment Variables

Create a .env file in backend/

PORT=5000
MONGODB_URI=your_mongodb_connection_string
SESSION_KEY=your_secret_key
BYTEZ_API_KEY=your_bytez_key
CLOUDINARY_URL=CLOUDINARY_URL=cloudinary://<your_api_key>:<your_api_secret>@<your_cloud_name>
NODE_ENV="production"

Create a .env file in frontend/
VITE_BASE_URI=your_server_base_uri (e.g: "http://localhost:5000")


▶️ Run Locally
Backend

cd backend
npm start

Frontend

cd frontend
npm run dev

App will run at:

Frontend: http://localhost:5173
Backend: http://localhost:5000
🧠 How It Works

User describes thumbnail idea
Prompt sent to Bytez AI
AI generates image
Image uploaded to Cloudinary
Saved to MongoDB
Displayed in user gallery
👨‍💻 Author
Sneha Chaudhary
