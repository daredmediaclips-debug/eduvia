# Eduvia React LMS Prototype

A front-end React/Vite prototype for an online Learning Management System.

## Included
- Role-based demo login: Student, Educator, Admin
- Dashboard overview
- Course browsing and enrollment (5-course cap demo)
- Course group display
- Learning materials list and study highlight/note
- Assessments list and educator analytics entry points
- Virtual class schedule and join/start actions
- Course chat UI
- Educator student list
- Admin user management, semester management and course creation
- Responsive layout

## Run locally
```bash
npm install
npm run dev
```

## Important
This is a UI prototype using mock data and local React state. It does not include authentication, database persistence, file upload storage, real assessment submission, permission enforcement on a server, real-time chat, or video conferencing. These should be implemented with a backend and appropriate services before production.

Suggested production stack:
- React + Vite + TypeScript
- Node.js API or Supabase
- PostgreSQL
- Object storage for files
- Auth provider with role-based access control
- WebSockets for chat
- Zoom/Google Meet/WebRTC for live classes
