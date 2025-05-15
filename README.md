Learning Management System (LMS)

A full-stack Learning Management System built with React, Node.js, Express, and MongoDB. This platform allows students to enroll in courses, educators to create and manage content, and admins to oversee system operations.

Features

 Student
- Register, login, and manage profile
- Browse, purchase, and enroll in courses
- Track course progress
- Watch video lectures
- Get course completion certificates

Educator
- Register and login with role-specific data (experience, courses handled)
- Add new courses with rich text descriptions
- Upload course videos and chapter-wise content
- Track enrollments and earnings via dashboard

Admin
- Login with email and password
- View total users, educators, and courses
- Manage users and courses
- Monitor earnings and system metrics

 Authentication
- Role-based authentication using Clerk 
- Secure login/signup flow with form validation
- Role-specific redirection (Student / Educator / Admin)
Tech Stack

Frontend:
- React.js
- Tailwind CSS
- Axios
- React Router
- React Quill (for rich text editor)
- Context API for state management

Backend:
- Node.js
- Express.js
- MongoDB
- Multer (for file uploads)
- Cloudinary (image/video hosting)
- Webhooks (for future Stripe/payment integration)

Deployment
- Vercel 

Installation

1. Clone the Repository
git clone https://github.com/Nithin833-M/LMS.git
cd LMS

2. Frontend Setup
-cd client
-npm install
-npm run dev

3. Backend Setup
-cd ../server
-npm install
-npm run dev

![image alt](https://github.com/Nithin833-M/LMS/blob/f4137200ffe72bb5d9343623c391dc2913ee62d8/Screenshot%202025-05-15%20163837.png)

![image alt](https://github.com/Nithin833-M/LMS/blob/f4137200ffe72bb5d9343623c391dc2913ee62d8/Screenshot%202025-05-15%20163902.png)

![image alt](https://github.com/Nithin833-M/LMS/blob/f4137200ffe72bb5d9343623c391dc2913ee62d8/Screenshot%202025-05-15%20163914.png)

![image alt](https://github.com/Nithin833-M/LMS/blob/f4137200ffe72bb5d9343623c391dc2913ee62d8/Screenshot%202025-05-15%20164049.png)
