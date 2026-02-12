# Alternative Medicine Center — Full Stack Project (Frontend + Backend)

A full-stack application for managing a clinic/center workflow:
- **Frontend**: React (Create React App)
- **Backend**: C# / .NET solution (BI / DAL / UI layers)

> Note: This project is for learning/demo purposes.

---

## Repositories
- Frontend: `alternativeMedicineFront`
- Backend: `altenativeMedicineBackend`

---

## Tech Stack
### Frontend
- React (Create React App)
- JavaScript / CSS / HTML

### Backend
- C# / .NET (Visual Studio solution)
- Layered architecture:
  - `UI` (presentation)
  - `BI` (business logic)
  - `Dal` (data access)

---

## Main Features (high level)
- Friendly UI for end users
- CRUD flows (create/read/update/delete) for core entities
- Client/server separation (React + API/Backend)
- Clear layering in backend (UI / BL / DAL)

---

## Project Structure
### Frontend (`alternativeMedicineFront`)
- `src/` – React app source
- `public/` – static files
- `package.json` – scripts and dependencies

### Backend (`altenativeMedicineBackend`)
- `AlternativeMedicineCenter.sln` – solution file
- `BI/`, `Dal/`, `UI/` – layered folders
- Local DB files (`.mdf/.ldf`) are included in the repo

---

## Getting Started

### Prerequisites
- Node.js + npm (for frontend)
- Visual Studio (for backend)
- .NET SDK (depending on the solution version)

---

## Run Frontend
```bash
cd alternativeMedicineFront
npm install
npm start

