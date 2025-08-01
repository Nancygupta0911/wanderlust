# Wanderlust 🌍

A full-stack travel listing platform inspired by Airbnb. Users can browse, create, and review listings, all powered by Node.js, Express, MongoDB, EJS (or React), and deployed to Render.


---
# 🔗 Live Demo:

[Click Here](https://project-wanderlust-u6a7.onrender.com/listings)

---

## Features ✨

- **User Authentication** – Sign up, log in, and log out using Passport.js (or JWT).
- **Listings Management** – Authenticated users can create, edit, and delete their own listings.
- **Reviews** – Add, view, and delete user reviews for each listing.
- **Image Upload** – Upload images stored via Cloudinary.
- **Interactive Maps** – Display location of listings using Mapbox (or Azure Maps) integration.
- **Search & Filter** – Search listings by title and use filters on homepage.
- **MIVC Architecture** – Organized in Models, Views, Controllers with middleware and validation (using Joi).
- **Responsive UI** – Designed with Bootstrap (or Tailwind) for mobile and desktop compatibility.
- **Robust Error Handling** – Global handlers and wrapped async routes ensure smooth UX.

---

## 🧰 Tech Stack

| Layer     | Technology |
|-----------|------------|
| Frontend  | HTML, CSS, JavaScript, EJS or React, Bootstrap / Tailwind  |
| Backend   | Node.js, Express.js, MVC pattern  |
| Database  | MongoDB with Mongoose |
| Authentication  | Passport.js (or JWT) |
| Image Storage  | Cloudinary |
| Maps API  | Mapbox or Azure Maps |
| Validation & Error Handling | Joi & custom Express middleware |

---

## 🛠️ Local Setup

1. **Clone Repository**  
```bash
   
git clone https://github.com/Nancygupta0911/wanderlust.git
cd wanderlust
   ```

 2. **Install Dependencies**

   ```bash
    npm install
   ```
  3.**Set Up Environment Variables (.env file):**
   ```bash
    MONGO_URI=your_mongodb_connection_string  
    CLOUDINARY_CLOUD_NAME=...  
    CLOUDINARY_API_KEY=...  
    CLOUDINARY_API_SECRET=...  
    MAPBOX_TOKEN=...  
    SESSION_SECRET=...  
   ```
   4.**Run the App**
   ```bash
    npm start
   ```

---
## 🧑‍💻 Author
Nancy Gupta

📧 [Gmail](nancygupta0911@gmail.com)

🌐 [Linkedln](https://www.linkedin.com/in/nancy-gupta-597100288/)



