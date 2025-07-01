# 🏡 Airbnb Clone - MERN Stack Project

This project is a full-stack Airbnb-style web application built as a part of my learning journey in the **MERN stack**. It allows users to register and list properties (Airbnbs), edit or delete their listings, view a map of locations, and leave comments on listings. The project emphasizes **authentication**, **authorization**, **security**, and clean **MVC architecture**.

---

## 📸 Live Preview

You can explore the live project here:  
🔗 **[https://travalto.onrender.com/listings](https://travalto.onrender.com/listings)**

### ✨ What You Can Do on the Live Site:

- Browse Airbnb-style listings with prices and locations
- View detailed listing pages with images and host info
- Create, edit, or delete your own listings after logging in
- Leave comments/reviews on listings
- Experience integrated Mapbox maps and Cloudinary-hosted images


## 🚀 Features

- 🔐 **Authentication** using **Passport.js**
- 👤 **Authorization** for route protection and user permissions
- 🗺️ **Map Integration** using **Mapbox**
- 🏠 **CRUD** operations for Airbnb listings:
  - Create new listings
  - Edit your listings
  - Delete your listings
- 💬 Comment system for users to leave reviews
- ☁️ **Image upload** and hosting using **Cloudinary**
- 🛠️ **MVC Architecture**: Clean separation of logic using Model-View-Controller pattern
- 💻 Built using:
  - **Express.js**
  - **Node.js**
  - **EJS** templating
  - **MongoDB** and **MongoDB Atlas**
  - **Bootstrap** for styling
- 🍪 Uses **Sessions**, **Cookies**, and **Flash Messages**
- 🌐 **Deployed on Render**
- 🧩 Middleware for route protection and validation

---

## 🧑‍💻 Technologies Used

| Tech | Purpose |
|------|---------|
| **MongoDB / MongoDB Atlas** | Database to store users, listings, and comments |
| **Express.js** | Server-side framework for routing and logic |
| **Node.js** | Runtime environment |
| **EJS** | Templating engine for server-rendered HTML |
| **Bootstrap** | Responsive UI and styling |
| **Passport.js** | User authentication (login/register/logout) |
| **Cloudinary** | Image storage and delivery |
| **Mapbox** | Map display and geolocation |
| **Express-session** | Managing user sessions |
| **Connect-flash** | Flash messages for alerts and notifications |
| **Cookie-parser** | To parse cookies for session tracking |
| **Middleware** | For authentication checks, error handling, and validations |

---

## 🏗️ Project Architecture

This project follows a clean **MVC (Model-View-Controller)** structure for scalability and maintainability.

```
📦 MainProject
├── 📁 controllers       # Controller logic (handles route logic)
├── 📁 init              # Initial setup logic (e.g., DB connection or seeds)
├── 📁 models            # Mongoose models for DB schemas
├── 📁 node_modules      # Installed dependencies (auto-generated)
├── 📁 public            # Static files (CSS, JS, images)
├── 📁 routes            # Express route definitions
├── 📁 utils             # Utility functions (e.g., geocoding, cloudinary config)
├── 📁 views             # EJS templates for frontend rendering
├── .gitignore           # Ignored files and folders
├── app.js               # Main application entry (Express config)
├── cloudconfig.js       # Cloudinary setup for image uploads
├── middleware.js        # Custom middleware (auth, flash, validation, etc.)
├── package.json         # Project metadata and scripts
├── package-lock.json    # Dependency lock file
├── schema.js            # Additional schema-related logic
```

---

## 🔗 Repository

GitHub Repository: [MainProject](https://github.com/joycrypt/MainProject.git)

---

## 💻 Local Development

To run the project locally:

1. **Clone the repository**
   ```bash
   git clone https://github.com/joycrypt/MainProject.git
   cd MainProject
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**

   Create a `.env` file in the root directory and include:

   ```env
   DATABASE_URL=your_mongodb_connection_string
   CLOUDINARY_CLOUD_NAME=your_cloudinary_name
   CLOUDINARY_KEY=your_cloudinary_key
   CLOUDINARY_SECRET=your_cloudinary_secret
   MAPBOX_TOKEN=your_mapbox_token
   SECRET=your_session_secret
   ```

4. **Run the development server**
   ```bash
   node app.js
   ```

5. Open your browser and visit: [http://localhost:8000](http://localhost:8000)

---


## 🙌 Acknowledgements

- [Mapbox](https://www.mapbox.com/)
- [Cloudinary](https://cloudinary.com/)
- [Passport.js](http://www.passportjs.org/)
- [Bootstrap](https://getbootstrap.com/)
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)

---
