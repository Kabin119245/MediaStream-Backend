# MediaStream-Backend

## Project Overview

This project is a comprehensive backend solution for a video hosting website, similar to YouTube. It is built using modern web technologies like **Node.js**, **Express.js**, **MongoDB**, **Mongoose**, **JWT**, **bcrypt**, and more. The project incorporates essential backend features, such as authentication, video uploads, user interactions, and video-related actions.

### Key Features:

- **Authentication & Authorization:**
  - Secure login and signup using **JWT** and **bcrypt**
  - Utilizes **access tokens** and **refresh tokens** for maintaining sessions
- **User Interactions:**
  - Like/Dislike videos
  - Comment and reply on videos
  - Subscribe and unsubscribe to channels
- **Video Management:**
  - Upload videos
  - Video streaming
  - Video metadata (title, description, tags)
- **Robust Security Practices:**
  - Password hashing with **bcrypt**
  - Token-based authentication with **JWT**

## Technologies Used:

- **Node.js**: Server-side JavaScript runtime
- **Express.js**: Web framework for Node.js
- **MongoDB**: NoSQL database for video and user data
- **Mongoose**: ODM for MongoDB
- **JWT**: JSON Web Token for authentication
- **bcrypt**: Password hashing
- **Other Libraries**: Multer (for file uploads), Cloudinary (optional for media storage)
