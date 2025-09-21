Project for Web programming
student-portal-template/
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── routes/
│   │   ├── models/     ← e.g. Students, Majors, Courses, Classes, Enrollments, RegistrationWindows, Announcements, Sessions
│   │   ├── middlewares/
│   │   ├── services/   ← business logic (session cleanup, time conflict check, etc.)
│   │   ├── utils/
│   │   └── index.ts
│   ├── Dockerfile
│   ├── package.json
│   └── .env.example
├── frontend/
│   ├── src/
│   │   ├── pages/
│   │   ├── components/
│   │   ├── api/
│   │   ├── hooks/
│   │   ├── contexts/    ← auth context, etc.
│   │   ├── styles/
│   │   └── App.tsx / index.tsx
│   ├── Dockerfile
│   ├── package.json
│   └── .env.example
├── docker-compose.yml
├── README.md
└── .gitignore

