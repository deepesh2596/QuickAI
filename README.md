# 🧠 QuickAI – Full-Stack AI SaaS Platform
🌐 **Live Demo**: https://quick-ai-chi-seven.vercel.app/

## Overview
QuickAI is a full-stack AI-powered SaaS application that offers a suite of AI tools like content generation (articles, blog titles), image generation, background and object removal, and resume review. The platform also features a community page where users can view and like public AI creations, and a personalized dashboard displaying user-specific history and work. Authentication and user management are handled using Clerk.
---

## 📌 Features

- ✍️ **Write Articles & Blog Titles using Google Gemini**
- 📄 **Resume Review via AI content parsing**
- 🖼️ **Generate Images from Prompts using ClipDrop API**
- 🧼 **Remove Background from uploaded images**
- 🚫 **Remove Specific Objects from images**
- 💬 **Community Page – View all public image creations**
- ❤️ **Like Functionality for each image**
- 👤 **User Dashboard – View your own generated content**
- 🔐 **Clerk Auth Integration – For secure user login**
- 🚀 **Deployed on Vercel**

## 🛠️ Tech Stack

### Frontend:
- **React.js**
- **Tailwind CSS**
- **react-hot-toast**
- **Axios**
- **Lucide-react**
- **react-markdown**
- **Vercel** (Deployment)

### Backend:
- **Node.js**
- **Express.js**
- **Neon (PostgreSQL) Database**
- **pdf-parse**
- **Cloudinary**
- **Google Gemini API**
- **multer**
- **open ai** 
- **Clerk** (Authentication & Role-based Authorization)

---


## 📦 Installation & Setup (Local Development)

# Clone the repository
git https://github.com/deepesh2596/QuickAI
cd client

# Install dependencies for backend
cd server
npm install

# Create a .env file and add the necessary environment variables
touch .env

# Example .env content (create .env using your credentials)

## **Frontend .env**
- VITE_CLERK_PUBLISHABLE_KEY= your_clerk_publishable
- VITE_BASE_URL=http://localhost:3000 (your backend url)

## **Backend .env**
- DATABASE_URL= your_neon_postgre_key
- CLERK_PUBLISHABLE_KEY= your_clerk_publishable
- CLERK_SECRET_KEY= your_clerk_secret_key
- GEMINI_API_KEY= your_gemini_api_key
- STRIPE_SECRET_KEY= your_stripe_secret
- CLIPDROP_API_KEY= your_clipdrop_api_key
- CLOUDINARY_CLOUD_NAME= your_cloudinary_cloud_name
- CLOUDINARY_API_KEY= your_cloudinary_api_key
- CLOUDINARY_API_SECRET= your_cloudinary_api_secret


# Start backend server
npm run server

# Go to frontend
cd ../client
npm install

# Start frontend
npm run dev

---


🙌 Acknowledgements
- Huge thanks to the dev community and open-source contributors for making tools like Clerk, openai, and clerk available.

📬 Contact
- Developer: Deepesh Chauhan
- Email: deepesh2596@gmail.com
- LinkedIn: linkedin.com/in/deepesh-chauhan


**It’s deployed live and ready to use — give it a try!**


