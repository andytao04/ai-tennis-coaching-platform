# Authentication & Roles

The product currently models two primary roles: **Player** and **Coach**.

Players manage their own dashboard, plans, logs, videos, notes, profile, assessments, and progression. Coaches can additionally manage trainee profiles and trainee-specific plans/logs/analysis workflows.

The private implementation uses password hashing with bcrypt, JWT-based authentication, httpOnly cookies, protected routes, and server-side authorization checks.

The data model distinguishes user-owned records from trainee-owned records so trainees do not need to behave exactly like independent login accounts.
