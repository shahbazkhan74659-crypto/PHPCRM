# Architecture

## Stack

- **Backend language:** PHP
- **Backend framework:** Laravel
- **Frontend:** Vue.js
- **Web server:** Nginx
- **Database:** PostgreSQL

**Web server plan:** Nginx is the intended web server, but it is set up later. Until then the app runs on PHP's built-in development server (`php artisan serve`, `http://127.0.0.1:8000`), which serves files and runs PHP in one process and is for local development only. With Nginx, the browser talks to Nginx, which serves static files itself and passes PHP requests to a PHP process (`php-cgi` on Windows, PHP-FPM on Linux); PHP runs Laravel and returns the response through Nginx.

How Vue.js connects to Laravel (Inertia/Vite-served pages, or a separate app calling a Laravel API) is not decided yet.

## Current Project Structure

As of 2026-11-21, `C:\learning\CRM` contains only documentation. No Laravel project, code or database exists yet.

```text
C:\learning\CRM
├── README.md          → short project note
└── docs
    ├── CLAUDE.md        → rules and the documentation system
    ├── PROJECT.md       → project definition
    ├── ARCHITECTURE.md  → system design (this file)
    ├── DECISIONS.md     → technical decisions (blank template)
    └── TASKS.md         → current tasks (blank template)
```

`PHASES.md` does not exist yet and is created only when the owner says so.

## Data Model

## Components and Boundaries

## Data Flow

## Everything Else
