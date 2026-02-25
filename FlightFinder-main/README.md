FLIGHT BOOKING APP (MERN STACK)


This is a full-stack Flight Booking Application built using the MERN (MongoDB, Express, React, Node.js) stack.

--------------------------------------------------------------------------------
📁 PROJECT STRUCTURE
--------------------------------------------------------------------------------

Flight-Booking-App-MERN-main/

│

├── backend/  # Express.js backend server

│   ├── config/                   # Configuration files (e.g., DB connection)

│   ├── controllers/              # Controller functions for routes

│   ├── middleware/               # Custom middleware (e.g., auth)

│   ├── models/                   # Mongoose models (User, Booking, Flight)

│   ├── routes/                   # API routes (auth, bookings, flights)

│   ├── utils/                    # Utility functions

│   ├── .env                      # Environment variables (example)

│   ├── server.js                 # Entry point for backend

│   └── package.json              # Backend dependencies and scripts

│

├── frontend/                     # React frontend application

│   ├── public/                   # Static assets

│   ├── src/

│   │   ├── components/           # Reusable React components

│   │   ├── pages/                # Page-level components (Home, Login, etc.)

│   │   ├── services/             # API service functions

│   │   ├── App.js                # Main App component

│   │   ├── index.js              # ReactDOM render entry point

│   │   └── App.css               # Styling

│   ├── .env                      # Environment variables (example)

│   └── package.json              # Frontend dependencies and scripts

│

├── README.txt                    # This file

└── .gitignore                    # Git ignored files list

--------------------------------------------------------------------------------
🚀 INSTALLATION & SETUP
--------------------------------------------------------------------------------

1. Clone the repository:
   git clone <repository_url>

2. Navigate to the root directory:
   cd Flight-Booking-App-MERN-main

3. Install backend dependencies:
   cd backend
   npm install

4. Set up backend environment variables:
   - Copy `.env.example` to `.env` and fill in required values.

5. Start the backend server:
   npm start

6. In a new terminal, install frontend dependencies:
   cd ../frontend
   npm install

7. Set up frontend environment variables:
   - Copy `.env.example` to `.env` and configure frontend API base URL.

8. Start the frontend React app:
   npm start

--------------------------------------------------------------------------------
🔧 TECHNOLOGIES USED
--------------------------------------------------------------------------------

- Frontend: React.js, Axios
- Backend: Node.js, Express.js
- Database: MongoDB (Mongoose)
- Auth: JWT, bcrypt
- Dev Tools: concurrently, nodemon, dotenv

--------------------------------------------------------------------------------
📌 NOTES
--------------------------------------------------------------------------------

- Ensure MongoDB is running locally or use a cloud DB (e.g., MongoDB Atlas).
- Both frontend and backend servers must be running for the app to work.
- Adjust CORS settings in backend if needed.

--------------------------------------------------------------------------------
📄 LICENSE
--------------------------------------------------------------------------------

This project is for educational and demonstration purposes.

# Flight-Booking-App-MERN
Demo - <a href="https://drive.google.com/file/d/1KtB_z6NDyo39xOchg242X2H3NaMgAKUE/view?usp=drive_link">view video</a>
ZIP FILE - <a href="https://drive.google.com/file/d/1WgVXGioYtnBC2-Kn9d6JfR1ONsgpPoZx/view?usp=drive_link">flight finder application zip file<a>
# Flight-Booking-App-MERN
Demo - <a href="https://drive.google.com/file/d/1Q0XwKtAz7EkaKNJv3_gbo6mZE9nfuBTK/view?usp=drive_link">view video</a>
