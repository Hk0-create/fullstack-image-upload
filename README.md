# Full-Stack Social Post Application

Ye aik Full-Stack application hai jo MERN Stack (MongoDB, Express, React, Node.js) par mushtamil hai. Is application ka main maqsad users ko posts create karne ki saholat dena hai, jis mein text ke sath images bhi upload ki ja sakti hain.

## 🚀 Features (Jo Aapne Code Mein Banaye Hain)

- **Create Post:** Frontend par `CreatePost.jsx` component use kiya gaya hai jahan user title aur image provide karta hai.
- **Secure API Endpoint:** Backend par POST request `/create-post` endpoint handle karta hai.
- **Image Processing:** Multer middleware (`upload.single('image')`) ka istemal kar ke image upload ko efficiently handle kiya gaya hai.
- **External Storage Integration:** `storage.service.js` file image buffer ko process kar ke aik external service (jaise Cloudinary) par upload karti hai aur image URL return karti hai.
- **Database Management:** Mongoose model `post.model.js` use kar ke image URL aur baqi post data ko MongoDB database mein save kiya jata hai.
- **Post Feed:** Frontend par `Feed.jsx` component display feed handle karta hai (fetching posts via API).

## 🛠️ Tech Stack

- **Frontend:** React.js, Vite.
- **Backend:** Node.js, Express.js.
- **Database:** MongoDB, Mongoose.
- **File Upload:** Multer.
- **Other:** Cors, Dotenv (for secure keys management).

## 💻 Setup and Installation Instructions

1.  **Repository Clone Karein:**

    ```bash
    git clone [YOUR_REPO_LINK]
    ```

2.  **Backend Setup:**
    - `cd Backend`
    - `npm install`
    - `.env.example` file ko dekh kar apni `.env` file banayein aur configuration (Mongo URI, Port, External Service Keys) set karein.
    - `npm run dev` start karne ke liye.

3.  **Frontend Setup:**
    - `cd Frontend`
    - `npm install`
    - `npm run dev` start karne ke liye.
"# fullstack-image-upload" 
