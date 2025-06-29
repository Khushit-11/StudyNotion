# StudyNotion 🎓

StudyNotion is a **fully functional ed-tech platform** built using the MERN stack (MongoDB, ExpressJS, ReactJS, NodeJS). It enables students to learn seamlessly, instructors to share their knowledge, and admins to oversee the platform. This project is designed to offer a modern, interactive, and user-friendly online learning experience.

## ✨ Features

### 👨‍🎓 For Students
- Browse and search courses
- View and purchase courses via Razorpay
- Access course content (videos, PDFs, etc.)
- Wishlist & cart management
- Edit user profile

### 👩‍🏫 For Instructors
- Dashboard with analytics
- Course creation & management
- View student feedback & ratings

### 🛡️ For Admin (Future Scope)
- Platform-wide insights
- Instructor & user management
- Revenue monitoring

## 🧱 Tech Stack

| Frontend  | Backend     | Database | Deployment | Other Integrations        |
|-----------|-------------|----------|------------|---------------------------|
| ReactJS   | Node.js     | MongoDB  | Vercel (Frontend) | Cloudinary (Media Storage) |
| Tailwind CSS | Express.js | MongoDB Atlas | Render / Railway (Backend) | Razorpay (Payments)         |
| Redux     | JWT Auth    | Mongoose |            | Figma (UI Design)          |

## 🧩 System Architecture

The platform follows a **client-server architecture**:
- Frontend communicates with the backend via **REST APIs**
- Backend handles authentication, media management, and business logic
- Database stores users, courses, and media content

## 📚 API Endpoints (Sample)

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST   | `/api/auth/signup`       | Register user              |
| POST   | `/api/auth/login`        | Login & return JWT token   |
| GET    | `/api/courses`           | Fetch all courses          |
| POST   | `/api/courses/:id/rate`  | Submit course rating       |
| PUT    | `/api/courses/:id`       | Update a course            |
| DELETE | `/api/courses/:id`       | Delete a course            |

## 🧪 Testing

- Manual and automated testing across critical workflows
- Uses frameworks like **Jest**, **Supertest**, or **Postman** for API validation

## 🚀 Deployment

| Service     | Purpose                  |
|-------------|--------------------------|
| Vercel      | Hosting frontend         |
| Render/Railway | Hosting backend        |
| MongoDB Atlas | Cloud database         |
| Cloudinary  | Image and media storage |
| Razorpay    | Payment processing       |

## 🔮 Future Enhancements

- Personalized learning paths
- Gamification (badges, leaderboards)
- Social learning (discussions, peer feedback)
- Mobile application (iOS & Android)
- ML-based course recommendations
- AR/VR immersive learning modules

## 📎 Design

UI/UX design is prototyped using [Figma] for consistency and modern design principles.

---

