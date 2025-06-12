🏥 Patient Appointment Booking System 📖 Overview A full-stack web application to manage doctor-patient appointments seamlessly. Patients can register, log in, and book, reschedule, or cancel appointments. Doctors (Admins) can manage and update appointment statuses.

This project is built using the MERN Stack (MongoDB, Express.js, React.js, Node.js) and secured using JWT authentication.

🚀 Tech Stack 🔧 Backend: Node.js

Express.js

MongoDB

Mongoose

JWT (JSON Web Tokens)

Dotenv

🎨 Frontend: React.js

React Router DOM

Context API

Tailwind CSS

🛠️ Setup Instructions 📦 Backend Setup Navigate to the backend folder: cd backend

Install dependencies: npm install

Create a .env file in the backend/ directory with the following content:

ini Copy Edit PORT=5000 MONGO_URI=mongodb://localhost:27017/appointmentdb JWT_SECRET=your_jwt_secret_key Start the backend server: npm run dev

💻 Frontend Setup Navigate to the frontend folder: cd frontend

Install dependencies: npm install

Start the frontend development server: npm start

🌐 Usage Open your browser and go to: http://localhost:3000

Sign up or log in as a Patient or Doctor

Patients can:

Book new appointments

Reschedule or cancel existing appointments

Doctors/Admins can:

View and manage all appointments

![Screenshot (939)](https://github.com/user-attachments/assets/f96544d6-01ca-4f4b-98bf-d43e9b7095d8)

![Screenshot (940)](https://github.com/user-attachments/assets/3d998184-e2fe-4e3a-81ce-7cbbd6465b22)

![Screenshot (941)](https://github.com/user-attachments/assets/b47b2676-f7cb-4608-927c-ed05961b0121)


