Presobo 🏥📅

Presobo is a full-stack doctor appointment booking platform designed to simplify healthcare scheduling. It allows patients to seamlessly book appointments, while doctors and admins can manage schedules and consultations from an intuitive dashboard.

Features 🚀

Patient Panel: Easy-to-use interface for patients to search, view, and book doctor appointments.

Doctor Panel: Doctors can manage availability, view patient bookings, and update consultation details.

Admin Dashboard: Centralized control for managing doctors, patients, and appointment records.

Secure Authentication: Role-based login system for patients, doctors, and admins.

Responsive Design: Optimized UI for desktop, tablet, and mobile devices.

Real-time Updates: Appointment confirmations and changes reflected instantly.

Scalable Backend: RESTful APIs to handle multiple concurrent requests.

Live Demo ✈️

Presobo Live Deployment

Technologies Used 🛠️

Frontend: React.js

Backend: Node.js, Express.js

Database: MongoDB

Authentication: JWT (JSON Web Token)

Styling: CSS, Tailwind (if used)

Deployment: Render / Vercel / Railway (depending on your hosting setup)

Prerequisites 🖍️

Node.js (v14 or above)

MongoDB installed or MongoDB Atlas account

NPM or Yarn

Installation 🖥️

Clone the repository:

git clone https://github.com/Aman2e/Presobo.git
cd Presobo


Install dependencies for both frontend and backend:

cd frontend
npm install
cd ../backend
npm install


Set up environment variables in a .env file for backend:

PORT=5000
MONGO_URI=your-mongodb-uri
JWT_SECRET=your-secret-key


Run the backend:

npm start


Run the frontend:

cd frontend
npm start


Open your browser and navigate to:

http://localhost:3000

How to Use 📖

Patients:

Register/Login

Search for doctors

Book, reschedule, or cancel appointments

Doctors:

Login with doctor credentials

Manage schedule and patient bookings

Admins:

Access the admin panel

Add/remove doctors

View/manage appointments and users

Project Structure 🔃
Presobo/
├── backend/                # Server-side code (Node.js + Express)
│   ├── models/             # MongoDB models
│   ├── routes/             # API routes
│   ├── controllers/        # Business logic
│   └── server.js           # Entry point
├── frontend/               # Client-side code (React)
│   ├── components/         # Reusable components
│   ├── pages/              # Patient/Doctor/Admin pages
│   ├── App.js              # Main app file
│   └── index.js            # React entry
├── package.json            # Dependencies
└── README.md               # Documentation

Contributing 🤝

Contributions are welcome! Please follow these steps:

Fork the repository.

Create a new branch:

git checkout -b feature-name


Commit your changes:

git commit -m "Add a meaningful commit message"


Push the branch:

git push origin feature-name


Create a pull request.

Known Issues 🐞

Limited doctor availability management features.

No integrated payment gateway (yet).

Future Enhancements 🛠️

Add payment integration for consultations.

Introduce notifications/reminders (email & SMS).

Support for telemedicine (video/audio consultations).

Advanced analytics for admins and doctors.

Contact 📨

Feel free to reach out for any questions or feedback:

Author: Aman Tiwari

GitHub: Aman2e

✨ Happy Booking with Presobo! ✨