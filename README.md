# # 🩺 Prescripto – Doctor Appointment Booking Platform

Prescripto is a full-stack web application built with the MERN stack (MongoDB, Express.js, React.js, and Node.js). It enables patients to easily book appointments with doctors, while also offering specialized dashboards for doctors and admins. The app supports online payments via Stripe and Razorpay and provides a streamlined experience across user types.

---

## 👥 User Roles

- **Patients**  
  - Browse doctors by specialty or location  
  - Book, reschedule, or cancel appointments  
  - View medical history and appointment summaries  
  - Edit personal profile  

- **Doctors**  
  - Approve/decline patient appointments  
  - Manage schedule and availability  
  - View earnings and patient history  
  - Edit doctor profile  

- **Admins**  
  - Add/approve/remove doctors  
  - View system analytics and appointments  
  - Manage users  

---

## 🔐 Features

- 🔒 Secure JWT-based authentication  
- 💳 Stripe & Razorpay payment integrations  
- 📅 Doctor availability scheduling  
- 📈 Admin dashboard with platform insights  
- 🌍 Location-based doctor filtering  
- 📸 Profile image upload for users and doctors  
- 📧 Email confirmations for appointments (if implemented)

---

## 🛠 Tech Stack

| Layer      | Technology                     |
|------------|--------------------------------|
| Frontend   | React, Tailwind CSS, Axios     |
| Backend    | Node.js, Express.js            |
| Database   | MongoDB + Mongoose             |
| Auth       | JWT, bcrypt                    |
| Payments   | Stripe, Razorpay               |
| Deployment | Vercel (Frontend), Render/Heroku (Backend) |

---

## 📂 Folder Structure

Prescripto/

├── backend/ # Node.js + Express server

│ ├── controllers/

│ ├── models/

│ ├── routes/

│ ├── middleware/

│ └── config/

├── frontend/ # React App

│ ├── src/

│ │ ├── components/

│ │ ├── pages/

│ │ ├── services/

│ │ └── utils/

└── README.md

