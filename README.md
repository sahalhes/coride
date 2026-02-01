# 🚗 CoRide Web Application

A **full-stack ridesharing web application** built using the **MERN stack (MongoDB, Express.js, React.js, and Node.js)**. The platform allows users to coordinate rides with friends or others traveling to similar destinations. Key features include trip creation, ride requests, and user profile management.

---

## ✨ Key Features

### 🔐 User Authentication
- Secure user registration and login
- User account and profile management

### 🚘 Trip Management
- Create trips with destination, date, and time details
- Browse public trips or trips created by friends
- Request to join trips
- Trip owners can approve or reject join requests

### 🗺️ Map Integration
- Interactive route planning and visualization
- Powered by **Mapbox** for real-time mapping and navigation

### 👤 Profile Customization
- Edit personal details such as username and profile picture
- View other users’ profiles

---

## 🛠️ Technology Stack

### Frontend
- **React.js**
- **Tailwind CSS** for a modern, responsive UI

### Backend
- **Node.js**
- **Express.js** for API handling and server-side logic

### Database
- **MongoDB** for storing users, trips, and messages

### Maps & Routing
- **Mapbox API** for map rendering and route visualization

---

## 🚀 Deployment & Infrastructure

### CI/CD Pipeline
- Automated with **GitHub Actions**
- Builds and pushes frontend and backend Docker images to **Docker Hub**

### Cloud Hosting
- Deployed on **AWS EC2**
- Managed via a GitHub Actions runner
- Uses an **Elastic Load Balancer (ELB)** with SSL for secure HTTPS traffic

### Security & Performance
- **Cloudflare** in front of the ELB
- Provides caching, DDoS protection, and performance optimization
