# Job Portal App with MERN Stack

A modern job portal application built with the MERN (MongoDB, Express.js, React.js, Node.js) stack. This app enables users to explore job listings, apply for positions, and manage their applications efficiently.

---

## 📚 Table of Contents
- [✨ Features](#features)
- [🛠 Technologies Used](#technologies-used)
- [🚀 Getting Started](#getting-started)
- [🤝 Contributing](#contributing)

---

## ✨ Features

- 🔒 **Secure Authentication**: Secure login and registration for both job seekers and employers using JWT (JSON Web Tokens).
- 📝 **Job Listings**: Easily browse and filter a diverse range of job postings stored in MongoDB.
- 📄 **Application Management**: Job seekers can track their applications, while employers can manage and review incoming applications.
- 📱 **Responsive Design**: Delivers a seamless and engaging experience across all devices.

## Technologies Used

- **Frontend:** React.js, React Router, Bootstrap for styling
- **Backend:** Node.js, Express.js, MongoDB for robust server-side operations
- **Authentication:** JWT (JSON Web Tokens), Bcrypt for password hashing
- **Image Management:** Cloudinary for efficient image uploads and storage
- **Deployment:** Vercel (frontend), Render (backend), MongoDB Atlas (database)

---

## 🚀 Getting Started

### Prerequisites
- Node.js (v22.2.0+)
- MongoDB Atlas or local MongoDB
- Cloudinary account

## Getting Started

Follow these steps to set up and run the project locally.

### Prerequisites

Ensure the following tools and accounts are available:
- Node.js (latest version or v22.2.0+)
- MongoDB Atlas account (or a local MongoDB server)
- Cloudinary account for image hosting

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/VidithAgarwal/JobFinder.git
   ```
2. **Install Dependencies**: Navigate to the project directories and install the required npm packages:
   ```sh
   cd JobFinder
   cd backend
   npm install
   cd..
   cd frontend
   npm install
   ```
3. **Set up environment variables:**
   - Create a `config.env` file after creating a `config folder` in the backend directory, containing the following variables:
   ```env
   PORT=
   CLOUDINARY_API_KEY=
   CLOUDINARY_API_SECRET=
   CLOUDINARY_CLOUD_NAME=
   FRONTEND_URL=
   DB_URL=
   JWT_SECRET_KEY=
   JWT_EXPIRE=
   COOKIE_EXPIRE=
   ```

   Replace each value with your specific configuration details.

4. Run the application:
   ```sh
   npm run dev
   ```
5. Open your browser and navigate to `http://localhost:5173` to view the app.
