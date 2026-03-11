Wandora Haven

Wandora Haven is a full-stack travel marketplace application that connects travelers with unique local stays. Built with the Node.js ecosystem, the platform allows users to list properties, explore destinations, leave reviews, and share travel experiences seamlessly.

## 🌐 Live Demo
https://wandora-haven.onrender.com/listings

🚀 Features
🔐 User Authentication

Secure signup and login system implemented using Passport.js with session management.

🏡 Property Management

Users can create, edit, and delete their own travel listings with ease.

⭐ Interactive Reviews

A dynamic review system where users can rate listings (1–5 stars) and leave comments.

☁️ Cloud Image Hosting

High-quality image uploads and storage powered by Cloudinary.

🗺️ Geolocation & Maps

Integrated Mapbox API to display property locations on interactive maps.

📱 Responsive UI

Mobile-friendly user interface built with Bootstrap 5 and EJS-Mate layouts.

🛡️ Data Validation

Robust server-side validation using Joi to ensure data integrity and security.

🛠️ Tech Stack
Frontend

EJS (Embedded JavaScript Templates)

Bootstrap 5

FontAwesome

Backend

Node.js

Express.js

Database

MongoDB Atlas (NoSQL)

Authentication

Passport.js (Local Strategy)

APIs & Services

Mapbox API (Maps & Geolocation)

Cloudinary (Image Storage)

📂 Project Structure

Wandora-Haven/
│
├── controllers/ # Route logic (MVC architecture)
├── init/ # Database seed data
├── models/ # Mongoose schemas (Listing, Review, User)
├── routes/ # Express route handlers
├── views/ # EJS templates for frontend
├── public/ # Static assets (CSS, JS, images)
├── utils/ # Custom error handlers & async wrappers
│
├── app.js # Main application entry point
├── cloudConfig.js # Cloudinary configuration
├── middleware.js # Custom middleware functions
├── schema.js # Joi validation schemas
│
├── package.json
├── package-lock.json
├── .gitignore
└── .env # Environment variables

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/wandora-haven.git
cd wandora-haven

2️⃣ Install Dependencies
npm install

3️⃣ Environment Variables

Create a .env file in the root directory and add the following:

CLOUD_NAME=your_cloudinary_name
CLOUD_API_KEY=your_api_key
CLOUD_API_SECRET=your_api_secret
MAP_TOKEN=your_mapbox_token
ATLASDB_URL=your_mongodb_atlas_url
SECRET=your_session_secret

4️⃣ Seed the Database (Optional)
node init/index.js

5️⃣ Start the Server
npm start

The application will run on:

http://localhost:8080

🚧 Future Improvements

Here are some features planned for future versions of Wandora Haven:

🧾 Booking System – Allow users to book properties with check-in and check-out dates.

💳 Payment Integration – Integrate payment gateways like Stripe or Razorpay for secure transactions.

❤️ Wishlist Feature – Users can save favorite listings for later.

🔎 Advanced Search & Filters – Filter listings by price, location, ratings, and amenities.

📊 Host Dashboard – Provide analytics for hosts such as bookings, reviews, and earnings.

🔔 Notifications System – Email or in-app notifications for bookings and reviews.

📍 Nearby Places Feature – Show attractions, restaurants, and transport near listings.

📱 Progressive Web App (PWA) – Enable installable mobile experience.

🛡️ Improved Security – Add rate limiting, helmet security headers, and CSRF protection.

🌍 Multi-language Support – Support multiple languages for global travelers.

📜 License

This project is licensed under the ISC License.

👨‍💻 Author

Taha Khan
