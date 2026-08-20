# API Overview

High-level API endpoints exposed by the CareerCure backend. Implementation details are intentionally omitted to protect intellectual property.

## Auth

```text
POST /register          — create a new account
POST /login             — sign in (email/password or Google OAuth)
POST /forgot-password   — request a password reset email
POST /reset-password    — reset password with OTP
```

## AI Career Counselor

```text
POST /chat              — chat with the AI career counselor
```

## Resume

```text
POST /resume            — upload / build resume
POST /resume/analyze    — AI-powered resume analysis
```

## Career Roadmap

```text
GET /roadmap            — generate personalized career roadmap
```

## Recommendations

```text
GET /internships        — semantically matched internships
GET /courses            — recommended courses
```

## Profile

```text
GET  /profile           — view user profile
PUT  /profile           — update user profile
```

## Admin (role-protected)

```text
GET    /admin/users     — list all users
GET    /admin/stats     — platform statistics & system health
PUT    /admin/users/{id}/activate   — activate / deactivate a user
PUT    /admin/users/{id}/promote    — promote a user to admin
GET    /admin/courses   — manage courses
GET    /admin/internships — manage internships
```
