# 📱 Social Media App

A full-featured social media platform designed and developed with a modern tech stack. Users can share posts, follow friends, like content, and engage with an intuitive and stylish UI.

## 🛠️ Features

- ✅ User Authentication (Sign up / Sign in / Sign out)
- ✅ User Profile Management
- ✅ Follow / Unfollow Users
- ✅ Real-time Posting & Feed
- ✅ Like & Comment Functionality
- ✅ Secure Backend with API Integration

## 📷 Screenshots

### 🔐 Login Page
<img width="736" alt="post_authentication" src="https://github.com/user-attachments/assets/54e1cf6b-164c-443f-93db-9dcd2aaf4d31" />

### 🏠 Home Feed
<img width="736" alt="create_postbutton" src="https://github.com/user-attachments/assets/16b7974f-52f8-4900-a72c-c4f10287dba9" />

## 🚀 Technologies Used

- **Frontend**: React.js, TailwindCSS, Redux
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (Mongoose)
- **Authentication**: JWT
- **Cloud Services**: Cloudinary for media uploads

## 🧱 Project Architecture

- `client/` – Frontend React code
- `server/` – Express backend code
- `config/` – Config files for DB and environment variables
- `models/` – MongoDB Mongoose Schemas
- `routes/` – API route definitions
- `controllers/` – Business logic handlers

## 🔧 Setup Instructions

```bash
# Clone the repo
git clone https://github.com/yourusername/social-media-app.git
cd social-media-app

# Setup Backend
cd server
npm install
npm run dev

# Setup Frontend
cd ../client
npm install
npm start
