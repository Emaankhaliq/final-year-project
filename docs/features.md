# Features

CareerCure is an AI-powered career development platform. Below is a summary of each major feature.

## AI Career Counselling

A conversational AI career counselor that answers career questions in real time. It uses an LLM (Groq + Llama 3) combined with retrieval-augmented generation (RAG) over a curated career knowledge base built with ChromaDB, so answers are grounded, relevant, and up to date.

## Resume Analysis

Users upload a resume (PDF) and receive AI-powered feedback instantly:

- Extracted skills from the resume
- Identified skill gaps relative to the target role
- Concrete suggestions for improvement

## AI Resume Builder

An assisted resume builder that helps users create a professional resume, with AI support for writing and polishing content.

## Personalized Roadmaps

Given the user's current skills and career goal, the system generates a step-by-step roadmap covering technologies, projects, and milestones to reach that goal.

## Course Recommendation

Courses from top learning platforms are recommended based on the user's profile and skill gaps, helping them close the distance to their target role.

## Internship Matching

Internships are semantically matched against the user's resume and skills, then ranked by how well they fit the profile.

## Authentication

Secure authentication flows:

- Email/password registration with OTP (one-time password) email verification
- Login with JWT sessions
- Password reset via email
- Google OAuth sign-in

## Dashboard

A user dashboard that brings everything together: profile status, resume analysis, roadmap, and internship/course recommendations in one place.

## Admin Portal

A dedicated, role-protected dashboard for platform administrators:

- **User Management** — view and search users, activate/deactivate accounts, promote users to admin
- **Content Management** — manage courses and internships listed on the platform
- **System Health** — real-time platform statistics, database status, and API documentation links
- **Secure Access** — admin-only access enforced with JWT-based role checks
