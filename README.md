# Job Portal



## Project Overview

The Job Portal is a full-stack MERN (MongoDB, Express, React, Node.js) application designed to streamline the hiring process for both recruiters and job seekers. Recruiters can create and manage job postings, while candidates can browse opportunities, apply for jobs, and track their application status.

The project follows a clean, scalable architecture with a separate frontend (React) and backend (Node + Express) communicating through secure REST APIs. MongoDB is used as the primary database to store user details, job listings, and application records.

This portal is built with real-world functionality in mind — including authentication, role-based access, dashboards, and responsive UI — making it suitable for learning, portfolio use, or further expansion into a production-grade application.

## Demo

_Add a link or screenshot here (e.g., GitHub Pages / Netlify / Vercel / deployed server)._

## Features

- Recruiter: create, edit, delete job postings
- Candidate: browse jobs, apply with resume, view application status
- Authentication (signup / login)
- Role-based access (recruiter / candidate)
- Search and filter jobs by location, role, and skills
- Dashboard for recruiters and candidates

## Tech Stack

- **Frontend:** React.js (hooks, components, context/state management)
- **Backend:** Node.js + Express.js (REST APIs)
- **Database:** MongoDB (Mongoose ODM)
- **Authentication:** JWT-based authentication


## Repository Structure

```
Job-Portal/
├── backend/           # server side code (API)
├── frontend/          # client side code
├── Readme.md          # this file
└── .gitignore
```

> If your repository uses different names or additional folders, update this section accordingly.



## Installation

### Clone

```bash
git clone https://github.com/krtanay7/Job-Portal.git
cd Job-Portal
```

### Backend Setup

1. Move to backend folder:

```bash
cd backend
```

2. Install dependencies (example using npm):

```bash
npm install
```

3. Create environment file (see [Environment Variables](#environment-variables)).

4. Start the backend server (example):

```bash
# development
npm run dev
# or
npm start
```


### Frontend Setup

1. Move to frontend folder:

```bash
cd ../frontend
```

2. Install dependencies (if applicable):

```bash
npm install
```

3. Start the frontend dev server (example):

```bash
npm start

```

## Environment Variables

Create a `.env` file in the `backend/` folder and add variables similar to:

```
PORT=5000
DATABASE_URL=<your-database-connection-string>
JWT_SECRET=your_jwt_secret_here
NODE_ENV=development
```

.


## Running the App

1. Start the backend (from `backend/`): `npm run dev`
2. Start the frontend (from `frontend/`): `npm start`
3. Open the frontend in the browser (usually at `http://localhost:3000` or `http://localhost:8080`) and the backend at `http://localhost:5000`.
`

## Deployment

- Backend: Deploy to Heroku / Render / Railway / DigitalOcean.
- Frontend: Deploy to Netlify / Vercel / GitHub Pages.

Make sure to set environment variables on the hosting platform.

## Contributing

Contributions are welcome! Please open an issue or pull request. Keep PRs small and focused, include descriptive commit messages and update this README if you add new functionality.

## License

Specify a license (e.g., MIT). If you don't have one yet, add an appropriate `LICENSE` file.

```
MIT License
```

## Contact

Project owner: **krtanay7**

If you'd like me to customize this README to exactly match the repo (list of npm scripts, exact env vars, DB used, sample `.env`), tell me and I will fetch the file list and create a fully tailored README.

