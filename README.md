# Obzen

Obzen is a modern, scalable web application built using contemporary web technologies. The project focuses on clean architecture, modular components, and maintainable code practices.

---

## GitHub Repository

https://github.com/KhyatiChahal/ObzenAssignment

---

## Working Demo (Hosted)

https://obzen.netlify.app

---

## Sample Data

```json
{
  "id": 101,
  "name": "Demo User",
  "email": "demo.user@example.com",
  "role": "User"
}
Architecture
The application follows a layered, component-based architecture to ensure separation of concerns and scalability.

Presentation Layer: Handles UI rendering and user interactions

Application Layer: Manages state and business logic

Service Layer: Responsible for API communication

Data Layer: Handles data models and persistence (if backend is used)

pgsql
Copy code
Client (Browser)
   ├── UI Components
   ├── State Management
   └── Routing
        |
Backend Server
   ├── REST APIs
   └── Database
Component Structure
css
Copy code
src/
├── components/
│   ├── Navbar.jsx
│   ├── Footer.jsx
│   └── Card.jsx
├── pages/
│   ├── Home.jsx
│   ├── Login.jsx
│   └── Dashboard.jsx
├── services/
│   └── api.js
├── styles/
│   └── main.css
└── App.js