Full-Stack Social Post Application
A robust MERN stack application that allows users to create and manage posts with integrated image uploads. This project demonstrates a complete flow from frontend form handling to backend storage and database management.

🚀 Features
Post Creation: A dedicated CreatePost.jsx component for user input (titles and images).

Secure API Endpoints: Backend POST requests handled via the /create-post endpoint.

Advanced Image Processing: Efficient file handling using Multer middleware (upload.single('image')).

Cloud Storage Integration: A specialized storage.service.js to process image buffers and upload them to external services (e.g., Cloudinary), returning a secure URL.

Database Management: Mongoose-driven post.model.js to store image URLs and metadata in MongoDB.

Dynamic Feed: Feed.jsx component to fetch and display all posts via API integration.

🛠️ Tech Stack
Frontend: React.js, Vite

Backend: Node.js, Express.js

Database: MongoDB, Mongoose

File Handling: Multer

Utilities: CORS, Dotenv (Environment Security)
