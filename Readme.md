
# 🎥 YouTube-like Backend API (Node.js + MongoDB)


A full-featured backend for a YouTube-like platform built using Node.js, Express, MongoDB, and Cloudinary. This project provides REST APIs for authentication, video upload, comments, likes, tweets, playlists, subscriptions, and dashboard analytics.
## 🚧 Project Status

Backend is complete. Frontend using React is currently in progress.
## 📌 About The Project


This is a complete backend system for a YouTube-like application. It supports user authentication, video uploads, playlists, comments, likes, subscriptions, tweets, and channel dashboard analytics.

The project is built following REST API architecture and MVC pattern with proper authentication, file uploads using Cloudinary, and MongoDB for data storage.
## 🛠 Built With

- Node.js  
- Express.js  
- MongoDB  
- Mongoose  
- Cloudinary  
- Multer  
- JWT  
## 🚀 Features

- User authentication (JWT with refresh token)
- Video upload with thumbnail
- Update and delete videos
- Toggle publish/unpublish video
- Comments system on videos
- Like system for videos, comments and tweets
- Tweet feature
- Playlist management
- Channel subscription system
- Dashboard analytics for channel
- Healthcheck API
## 📁 Project Structure

```bash
src/
 ├── controllers/
 ├── models/
 ├── routes/
 ├── middlewares/
 ├── utils/
 ├── db/
 ├── app.js
 └── index.js
```
## ▶️ Getting Started

### Prerequisites

- Node.js
- MongoDB

### Installation

```bash
git clone https://github.com/satakshi003/youtube-like-backend.git
cd youtube-like-backend
npm install
npm run dev
```

## 🔐 Environment Variables

Create a `.env` file in the root folder:

```env
PORT=8000
MONGODB_URI=your_mongodb_connection_string

ACCESS_TOKEN_SECRET=your_access_token_secret
REFRESH_TOKEN_SECRET=your_refresh_token_secret

CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_key
CLOUDINARY_API_SECRET=your_cloudinary_secret
```
## 🧪 API Testing

All APIs were tested using Postman including:

- User APIs  
- Video APIs  
- Comment APIs  
- Like APIs  
- Playlist APIs  
- Tweet APIs  
- Subscription APIs  
- Dashboard APIs  

## 🧠 What I Learned

- How to structure a scalable backend
- How JWT authentication works
- How to upload files using Multer and Cloudinary
- How to design REST APIs
- How to work with MongoDB relations and aggregation
## 📌 Future Improvements

- Add frontend using React
- Add search & recommendation system
- Add video streaming optimization
## 👩‍💻 Author

**Satakshi Subhasmita**  
GitHub: https://github.com/satakshi003

