


# CodeSync – Real-Time Collaborative Code Editor

## Table of Contents

- [About](#about)  
- [Features](#features)  
- [Tech Stack](#tech-stack)  
- [Architecture & Folder Structure](#architecture--folder-structure)  
- [Setup & Installation](#setup--installation)  

---

## About

**CodeSync** is a real-time collaborative code editor that enables multiple users to edit the same code document simultaneously. It provides live cursor positions, instant content synchronization, and a simple frontend/backend separation for easy development and deployment. Collaboration is implemented via WebSockets (Socket.IO or equivalent).

---

## Features

- Real-time collaborative editing (multiple users)  
- Live cursor presence and selection sync  
- Document/session join and leave  
- Basic validations (non-empty documents, simple conflict handling)  
- Responsive UI built with React + Vite  
- Clean separation of frontend and backend

(*You may add more features you have implemented: e.g., file sharing, persistence, authentication, syntax highlighting, language support, version history, etc.*)

---

## Tech Stack

| Layer        | Technologies / Libraries                                           |
|--------------|--------------------------------------------------------------------|
| Frontend     | React, Vite, HTML, CSS, JavaScript                                 |
| Backend      | Node.js, Express.js (or plain Node)                                |
| Real-Time    | Socket.IO (or equivalent WebSocket library)                        |
| Communication | REST APIs (if any)                                                 |
| Others       | nodemon, CORS, dotenv, ESLint                                       |

---

## Architecture & Folder Structure

A typical structure for this project:

```
CodeSync-Real-Time-Collaborative-Code-Editor/
├── backend/
│   ├── index.js
│   ├── package.json
│   ├── routes/
│   ├── controllers/
│   └── utils/
├── frontend/
│   ├── index.html
│   ├── package.json
│   ├── src/
│   │   ├── main.jsx
│   │   ├── App.jsx
│   │   └── assets/
│   └── public/
├── .gitignore
└── README.md
```

- **backend/** — server-side code that handles sockets and any APIs  
- **frontend/** — Vite + React client  
- **index.js** — backend entrypoint (may be named `server.js` in other projects)  
- **src/** — React source files for the frontend

---

## Setup & Installation

### Prerequisites

- Node.js (v14+ recommended; v18+ preferable)  
- npm or yarn  
- (Optional) A modern browser for the frontend

### Installation Steps

1. Clone the repo:

```bash
git clone https://github.com/Shrutisingla130/CodeSync-Real-Time-Collaborative-Code-Editor.git
cd CodeSync-Real-Time-Collaborative-Code-Editor
```

2. Install backend dependencies:

```bash
cd backend
npm install
```

3. Install frontend dependencies:

```bash
cd ../frontend
npm install
```

4. Return to project root (optional):

```bash
cd ..
```

### Running the Project (Development)

- Start backend (from `backend` folder):

```bash
cd backend
# if a start script exists
npm start

# or run directly
node index.js
```

- Start frontend (from `frontend` folder):

```bash
cd frontend
npm run dev
```

Open the URL printed by the Vite dev server (commonly `http://localhost:5173`). The backend typically listens on a port such as `3000` or `4000` — check `backend/index.js` or `backend/package.json` for the actual port.

---

If you'd like, I can update the README to show exact `npm` scripts and port numbers by reading `backend/package.json` and `frontend/package.json` and inserting the precise commands. I can also add a `LICENSE`, Dockerfile, or GitHub Actions CI next.


1. Clone the repo:

 ```bash
   git clone https://github.com/megha-ra/LinkUp-RealTime-Chat-Webapp.git
   cd LinkUp-RealTime-Chat-Webapp
````

2. Install backend dependencies:

 ```bash
 cd backend
 npm install
 ```

3. Install frontend dependencies (if you have any, e.g. build tools, bundlers):

 ```bash
 cd ../frontend
 npm install
 ```

4. Return to project root:

 ```bash
 cd ..
 ```