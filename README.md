# Presobo 🏥📅  

**Presobo** is a full-stack doctor appointment booking platform designed to simplify healthcare scheduling. It allows patients to seamlessly book appointments, while doctors and admins can manage schedules and consultations from an intuitive dashboard.  

---

## Features 🚀  

- **Patient Panel**: Easy-to-use interface for patients to search, view, and book doctor appointments.  
- **Doctor Panel**: Doctors can manage availability, view patient bookings, and update consultation details.  
- **Admin Dashboard**: Centralized control for managing doctors, patients, and appointment records.  
- **Secure Authentication**: Role-based login system for patients, doctors, and admins.  
- **Responsive Design**: Optimized UI for desktop, tablet, and mobile devices.  
- **Real-time Updates**: Appointment confirmations and changes reflected instantly.  
- **Scalable Backend**: RESTful APIs to handle multiple concurrent requests.  

---

## Live Demo ✈️  

[Presobo Live Deployment](https://presobo-frontend.onrender.com)  

---

## Technologies Used 🛠️  

- **Frontend**: React.js  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB  
- **Authentication**: JWT (JSON Web Token)  
- **Styling**: CSS, Tailwind (if used)  
- **Deployment**: Render   

---

## Prerequisites 🖍️  

- Node.js (v14 or above)  
- MongoDB installed or MongoDB Atlas account  
- NPM or Yarn  

---

## Installation 🖥️  

1. Clone the repository:  
   ```bash
   git clone https://github.com/Aman2e/Presobo.git
   cd Presobo
   ````


2. Install dependencies for both frontend and backend:

   ```bash
   cd frontend
   npm install
   cd ../backend
   npm install
   ```
   

3. Set up environment variables in a `.env` file for backend:

   ```plaintext
   PORT=5000
   MONGO_URI=your-mongodb-uri
   JWT_SECRET=your-secret-key
   ```
   

4. Run the backend:

   ```bash
   npm start
   ```

5. Run the frontend:

   ```bash
   cd frontend
   npm start
   ```

6. Open your browser and navigate to:

   ```
   http://localhost:3000
   ```

---

## How to Use 📖

1. **Patients**:

   * Register/Login
   * Search for doctors
   * Book, reschedule, or cancel appointments

2. **Doctors**:

   * Login with doctor credentials
   * Manage schedule and patient bookings

3. **Admins**:

   * Access the admin panel
   * Add/remove doctors
   * View/manage appointments and users

---

## Project Structure 🔃

```plaintext
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
```

---

## Contributing 🤝

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch:

   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:

   ```bash
   git commit -m "Add a meaningful commit message"
   ```
4. Push the branch:

   ```bash
   git push origin feature-name
   ```
5. Create a pull request.

---

## Known Issues 🐞

* Limited doctor availability management features.
* No integrated payment gateway (yet).

---

## Future Enhancements 🛠️

* Add payment integration for consultations.
* Introduce notifications/reminders (email & SMS).
* Support for telemedicine (video/audio consultations).
* Advanced analytics for admins and doctors.

---

## Contact 📨

Feel free to reach out for any questions or feedback:

* **Author**: Aman Tiwari
* **GitHub**: [Aman2e](https://github.com/Aman2e)
* **Gmail**: amanmmmut0@gmail.com

---

✨ Happy Booking with Presobo! ✨


