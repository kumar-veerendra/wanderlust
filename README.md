# 🌍 Wanderlust – MERN Stack Travel Blog Platform

Wanderlust is a full-stack web application inspired by Airbnb and travel blog platforms. It allows users to explore destinations, view location-based listings, and add their own travel experiences. This project demonstrates real-world implementation of the MERN stack (MongoDB, Express.js, React.js, Node.js), including secure authentication, map integration, and RESTful APIs.

![Wanderlust UI Screenshot](https://your-screenshot-link-if-available.com)

---

## 🚀 Features

- 🔐 **User Authentication** – Signup/Login system with secure sessions or JWT
- 📌 **Location Integration** – Map-based post locations using Mapbox or Leaflet
- 🗺️ **Explore Listings** – Users can view, search, and filter travel experiences
- ✍️ **Create & Edit Posts** – Authenticated users can add, edit, or delete listings
- 📷 **Image Uploads** – Post attractive images using Cloudinary or local storage
- 📱 **Responsive UI** – Fully mobile-friendly with a modern design
- 🌐 **RESTful API** – Clean separation of backend routes for scalability

---

## 🧑‍💻 Tech Stack

| Frontend  | Backend       | Database | Tools & APIs           |
|-----------|---------------|----------|-------------------------|
| React.js  | Node.js       | MongoDB  | Mapbox / Leaflet        |
| Tailwind / CSS | Express.js | Mongoose | Cloudinary (optional)   |
| Axios     | JWT / Session | Dotenv   | Git, GitHub             |

---

## 🏁 Getting Started

### ⚙️ Prerequisites

- Node.js and npm
- MongoDB Atlas (or local MongoDB)
- Mapbox API key
- (Optional) Cloudinary account for image hosting

### 🔧 Installation

```bash
# Clone the repository
git clone https://github.com/kumar-veerendra/wanderlust.git
cd wanderlust

# Install backend dependencies
cd backend
npm install

# Set up environment variables
cp .env.example .env
# Add your MongoDB URI, Mapbox key, Cloudinary credentials, etc.

# Run the backend
npm run dev

# Open a new terminal for frontend
cd ../frontend
npm install

# Run the frontend
npm start


## 📁 Folder Structure
wanderlust/
│
├── backend/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   └── server.js
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.js
│
└── README.md


## 🔐 Environment Variables (.env)
MONGODB_URI=your_mongodb_connection_string
MAPBOX_TOKEN=your_mapbox_api_key
JWT_SECRET=your_jwt_secret_key
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_secret


## 🚀 Deployment
- Frontend: Netlify, Vercel
- Backend: Render, 
- Database: MongoDB Atlas

## ✅ Future Improvements
- Add a Booking System
- User Profile & Dashboard
- Review & Rating System
- Pagination & Sorting
- Email Notifications

## 📸 Demo
🔗 Live Demo Link (if hosted)

## 🤝 Contributing
Contributions are welcome! Please open issues or submit pull requests for improvements or feature requests.

## 🙌 Acknowledgements
- Inspired by Airbnb UI
- Map data by Mapbox
- Built with ❤️ using MERN stack

