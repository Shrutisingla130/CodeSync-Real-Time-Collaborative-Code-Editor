


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

---

## Tech Stack

| Layer        | Technologies / Libraries                                           |
|--------------|--------------------------------------------------------------------|
| Frontend     | React, Vite, HTML, CSS, JavaScript                                 |
| Backend      | Node.js, Express.js                                                |
| Real-Time    | Socket.IO                                                           |

---

## Architecture & Folder Structure

A typical structure for this project:

```
CodeSync-Real-Time-Collaborative-Code-Editor/
├── backend/
│   └── index.js
├── frontend/
│   ├── index.html
│   ├── package.json
│   ├── src/
│   │   ├── main.jsx
│   │   ├── App.jsx
│   │   ├── App.css
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
cd ../backend
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
npm run dev
```

- Start frontend (from `frontend` folder):

```bash
cd frontend
npm run dev
```


1. Clone the repo:

 ```bash
   git clone https://github.com/Shrutisingla130/CodeSync-Real-Time-Collaborative-Code-Editor
   cd CodeSync-Real-Time-Collaborative-Code-Editor
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