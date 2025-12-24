# DevMetrics

DevMetrics is a GitHub analytics dashboard that securely connects to a user’s GitHub account and visualizes meaningful development activity such as commit trends and repository data.

The project is built with a **production-style architecture**, focusing on **security, correctness, and clarity** rather than superficial features.

---

## 🔹 Key Highlights (For Recruiters)

- Implemented **GitHub OAuth (Authorization Code Flow)** correctly
- Clear **frontend–backend separation**
- Secure handling of secrets using environment variables
- Real-world API consumption and data transformation
- Clean React architecture using hooks and routing

---

## 🧠 What This Project Demonstrates

- Understanding of OAuth authentication and security boundaries
- Ability to design and implement REST-based systems
- Practical React skills (state, effects, routing)
- Backend fundamentals with Express and middleware
- Thoughtful UI decisions focused on data clarity

---

## 🛠 Tech Stack

### Frontend

- React (Vite)
- React Router
- Axios
- CSS / Tailwind (minimal, no UI libraries)

### Backend

- Node.js
- Express
- Axios
- dotenv
- cors

### External Services

- GitHub REST API
- GitHub OAuth (Authorization Code Flow)

---

## 🔐 Authentication Flow (High Level)

1. User initiates GitHub OAuth from frontend
2. GitHub redirects back with an authorization code
3. Frontend sends code to backend
4. Backend exchanges code for access token securely
5. Backend fetches GitHub data
6. Frontend renders analytics

> Access tokens and secrets are never exposed to the frontend.

---

## 📊 Current Features (MVP)

- GitHub OAuth integration
- OAuth callback handling
- Secure frontend → backend communication
- Commit activity retrieval and transformation
- Basic analytics visualization
