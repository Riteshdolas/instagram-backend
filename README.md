# 📸 Instagram - Backend

This is the **backend server** for an Instagram clone built with Node.js, Express.js, and MongoDB.  
It handles user authentication, posting, commenting, liking, following, messaging, and more.

---

## 🚀 Tech Stack

- **Node.js**
- **Express.js**
- **MongoDB**
- **JWT (Authentication)**
- **Multer (File Uploads)**
- **Cloudinary (Image Hosting)**

---
## 🔧 Installation & Setup

```bash
 
# 1. Clone the repository
git clone https://github.com/Riteshdolas/instagram-backend.git

# 2. Navigate to the project folder
cd instagram-backend

# 3. Install dependencies
npm install

# 4. Start the development server
npm run dev
```
---
## 🔐 Create a .env file

PORT=             
CLOUD_NAME=   
CLOUD_API_KEY=                 
CLOUD_API_SECRET=       
JWT_ACCESS_SECRET=            
MONGODB_URL=    

---
## 📁 Project Structure 
src/                   
├── controllers/       → Logic for user, post, comment, story, etc.             
├── middlewares/       → Custom middlewares (auth, multer, token)   
├── routes/            → All API route definitions (user.routes.js)       
├── models/            → Mongoose schemas for User, Post, Comment, etc.     
├── utils/             → Utility functions          
├── db/            → DB connection, Cloudinary config, etc.       
├── server.js           → App entry point
