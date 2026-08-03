# Gamage Recruiters Job Portal System

Public development workspace for the Gamage Recruiters Job Portal System, a MERN-based recruitment and application-management platform developed by the Software Engineering Team.

## Development Phase

Weeks 05–06 focus on implementing and integrating the approved Minimum Viable Product (MVP).

## Technology Stack

- **Frontend:** React, Vite, JavaScript, Tailwind CSS, React Router, Axios, React Hook Form and Zod
- **Backend:** Node.js, Express.js, JavaScript, REST APIs, JWT, bcrypt, Multer and Nodemailer
- **Database:** MongoDB Atlas with Mongoose
- **Media Storage:** Cloudinary
- **Deployment Direction:** Vercel for the frontend and Render for the backend

## Repository Structure

```text
client/    React frontend
server/    Node.js and Express backend
docs/      Project documentation
.github/   Repository governance files and templates
```

## Branches

- `main` contains stable, release-ready code.
- `develop` is the main integration branch during development.
- Normal development work must use a task branch and a pull request into `develop`.

## Security Notice

This is a public repository. Never commit credentials, `.env` files, MongoDB connection strings, JWT secrets, email credentials, Cloudinary credentials, API keys, personal access tokens, real CVs, personal data, private company documents, database exports, production logs or private Postman environments.

Use only safe placeholders in `.env.example` files.

## Contribution Rules

Read [CONTRIBUTING.md](CONTRIBUTING.md) before making changes.

## Licence

No licence is currently included. A licence may only be added after company or supervisor approval.
