<div align="center">

<img src="public/logo/join-logo.svg" alt="Join logo" width="130">

# Join

### Kanban Task Management | Angular & Supabase

A collaborative task-management application for organizing work, tracking progress and coordinating tasks.

**Team project developed during the Developer Akademie program.**

[![Angular](https://img.shields.io/badge/Angular-21-DD0031?logo=angular&logoColor=white)](https://angular.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.9-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Supabase](https://img.shields.io/badge/Supabase-PostgreSQL-3ECF8E?logo=supabase&logoColor=white)](https://supabase.com/)

**[Live Demo](https://join.juliakeller-dev.de/login) · [Source Code](https://github.com/JuliaKeller13/Join) · [Original Team Repository](https://github.com/JensBaumannDev/Join)**

</div>

---

## Table of Contents

- [About the Project](#about-the-project)
- [Features — Team Project](#features--team-project)
- [My Contributions — Julia Keller](#my-contributions--julia-keller)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Team & Credits](#team--credits)

---

## About the Project

Join is a Kanban-style web application that helps users organize tasks and monitor their progress. The application was developed collaboratively by a four-person team. It uses **Angular and TypeScript** for the frontend and **Supabase** for authentication and data persistence.

This repository is my fork of the [shared team repository](https://github.com/JensBaumannDev/Join). The features below describe the **combined team result**; my own implementation work is listed separately under *My Contributions*.

## Features — Team Project

- **Authentication:** Sign up, log in and explore the application with a guest account.
- **Kanban board:** Track tasks across *To do*, *In progress*, *Await feedback* and *Done*.
- **Task management:** Create, edit, assign and prioritize tasks; manage subtasks and due dates.
- **Drag and drop:** Move and reorder tasks on the board.
- **Contacts:** Manage a contact directory and assign contacts to tasks.
- **Summary dashboard:** View task statistics and an overview of ongoing work.
- **Responsive interface:** Use the application on desktop and mobile devices.

## My Contributions — Julia Keller

The following work is supported by my commits in the shared Git history:

- **Login and registration interfaces:** Developed and refined the Angular login and sign-up pages, including reactive forms, input validation, password visibility and responsive styling.
- **Authentication user experience:** Implemented guest login, improved error and loading states, and contributed fixes to session initialization and route protection.
- **Kanban workflow:** Improved task creation and editing interfaces, and implemented persistence of task ordering through the task service after drag-and-drop operations.
- **UI and usability:** Refined animations, form styling, dialog layouts and mobile/iOS compatibility; made targeted improvements to the contact list.
- **Team collaboration:** Integrated changes through the shared Git workflow and contributed fixes during testing and integration.

These are **selected contributions**, not a claim of sole authorship of the application. Other functionality was implemented collaboratively or by other team members.

## Tech Stack

| Area | Technologies |
| --- | --- |
| Frontend | Angular 21, TypeScript, HTML, SCSS |
| UI and state | Angular Signals, Reactive Forms, Angular Material / CDK |
| Authentication and data | Supabase, PostgreSQL |
| Tooling | Git, npm, Vitest, Compodoc |

## Getting Started

### Requirements

- Node.js and npm compatible with Angular 21
- Access to a configured Supabase project for authentication and data storage

### Local setup

```bash
git clone https://github.com/JuliaKeller13/Join.git
cd Join
npm install
```

Review the Supabase configuration in `src/environments/environment.ts` and configure your own project as needed. Use only a **public/publishable Supabase client key** in frontend code; never place a service-role or other secret key in the browser application.

Run the development server:

```bash
npm start
```

Open `http://localhost:4200/`.

### Tests and documentation

```bash
npm test
npm run docs
```

The documentation command starts the Compodoc documentation server. Test execution requires the dependencies and configuration described above.

## Project Structure

```text
src/
├── app/
│   ├── components/     # Reusable UI components and dialogs
│   ├── guards/         # Route protection
│   ├── pages/          # Login, signup, board, tasks, contacts and summary
│   ├── services/       # Authentication, tasks, contacts and Supabase access
│   ├── interfaces/     # Application data types
│   └── app.routes.ts   # Application routes
├── environments/      # Supabase environment configuration
└── styles/            # Shared SCSS styles
public/                # Icons, logos and fonts
```

## Team & Credits

Join was developed collaboratively by four developers during the **Developer Akademie** program. All contributors are credited below.

| Contributor | GitHub | LinkedIn |
| :--- | :--- | :--- |
| **Jens Baumann** | [@JensBaumannDev](https://github.com/JensBaumannDev) | [Jens Baumann](https://www.linkedin.com/in/jens-baumann-7a6866315/) |
| **Julia Keller** | [@JuliaKeller13](https://github.com/JuliaKeller13) | [Julia Keller](https://www.linkedin.com/in/julia-keller-970409389/) |
| **Temirlan Gashimov** | [@TemirlanGashimov](https://github.com/TemirlanGashimov) | [Temirlan Gashimov](https://www.linkedin.com/in/temerlan-gashimov-8927291b2) |
| **Mario Ramirez** | [@marioramirez90](https://github.com/marioramirez90) | [Mario Ramirez](https://www.linkedin.com/in/mario-ramirez-668288283) |

**[Original Team Repository](https://github.com/JensBaumannDev/Join)** · [My GitHub Fork](https://github.com/JuliaKeller13/Join)

This fork presents the **shared team project** and documents my individual contributions above; it does not claim sole authorship.

---

<div align="center">

**Julia Keller** · [Portfolio](https://juliakeller-dev.de/) · [GitHub Profile](https://github.com/JuliaKeller13)

</div>
