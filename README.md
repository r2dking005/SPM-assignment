# AI-Powered Personalized Learning Platform

A web-based adaptive learning system that gives every learner a study path matched to what they already know. Learners take an initial assessment, receive a personalized study plan, practice through daily tasks, and get help from an AI learning assistant, while points, streaks, and badges keep them motivated.

> **Course:** CS4002 Fundamentals of Software Project Management
> **Institution:** FAST-NUCES, Chiniot-Faisalabad Campus
> **Section:** BSCS-9C
> **Instructor:** Ms. Maham Saleem

---

## Table of Contents

- [Project Purpose](#project-purpose)
- [Group Members](#group-members)
- [Key Features](#key-features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Jira and GitHub Workflow](#jira-and-github-workflow)
- [Scope](#scope)
- [Project Links](#project-links)

---

## Project Purpose

Most online learning platforms give every user the same course sequence, whether they are complete beginners or already experienced. This makes learning less efficient and harder to stay consistent with.

This project addresses that problem by:

- Assessing the learner's existing knowledge and building a **personalized study plan**
- **Adapting difficulty** based on daily assessment performance
- Tracking **progress** through a course roadmap
- Providing an **AI learning assistant** to clarify difficult concepts
- Encouraging regular study through **gamification** (points, streaks, badges, leaderboard)

**Target users:** students and independent learners who want a structured, personalized way to learn courses.

---

## Group Members

| Name | Student ID | Role |
|---|---|---|
| Ali Ahmed | 22F-0505 | Project Manager & Backend Developer |
| Muhammad Ahmad | 22F-3866 | Frontend Developer & UI/UX Designer |

Both members share responsibility for requirement analysis, system design, testing, documentation, Jira management, integration, and the final demonstration.

---

## Key Features

The project is organized into three Epics, matching our Jira backlog.

### 1. User Authentication & Onboarding
- User registration and secure login
- Personalized dashboard
- Course search and enrollment
- New learner / prior-knowledge selection
- Initial knowledge assessment and learner-level identification
- Personalized study-plan generation

### 2. Adaptive Learning Engine
- Course roadmap with current position and overall progress
- Daily learning tasks (MCQ and problem-solving assessments)
- Assessment result calculation
- Adaptive difficulty adjustment and additional practice
- Topic progression
- AI-powered learning assistant for course-related questions

### 3. Gamification & Engagement
- Points and daily streaks
- Achievements and badges
- Leaderboard
- Basic learner community
- Learning notifications

---

## Technologies Used

> Update this section to match the stack your team actually uses.

| Layer | Technology |
|---|---|
| Frontend | React.js, HTML5, CSS3, JavaScript |
| Backend | Node.js, Express.js |
| Database | MongoDB |
| AI Service | External AI/LLM API (learning assistant) |
| Version Control | Git, GitHub |
| Project Management | Jira (Scrum) |

---

## Project Structure

> Adjust folder names to match your repository.

```
.
├── backend/              # Server code: APIs, models, controllers, routes
├── frontend/             # Client application: pages, components, styles
├── docs/                 # Project documentation and diagrams
├── .gitignore
└── README.md
```

---

## Getting Started

> Replace the commands below with your actual setup steps once the code is in place.

### Prerequisites
- Node.js (v18 or later) and npm
- MongoDB (local installation or a cloud connection string)
- Git

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>

# 2. Install backend dependencies
cd backend
npm install

# 3. Install frontend dependencies
cd ../frontend
npm install
```

### Environment Variables

Create a `.env` file inside `backend/` (do not commit it):

```
PORT=5000
MONGODB_URI=<your-mongodb-connection-string>
JWT_SECRET=<your-secret-key>
AI_API_KEY=<your-ai-service-key>
```

### Running the Project

```bash
# Start the backend
cd backend
npm start

# Start the frontend (in a second terminal)
cd frontend
npm start
```

---

## Jira and GitHub Workflow

This repository is connected to our Jira Scrum project so that every code change can be traced back to a work item.

**Branch naming:** `JiraIssueKey-short-description`

```
SCRUM-13-user-login
SCRUM-14-course-search
```

**Commit messages:** start with the Jira issue key

```
SCRUM-13 Add login form UI
SCRUM-13 Implement login API endpoint
```

**Pull requests:**
- Include the Jira issue key in the PR title
- Describe what changed and which issue it addresses
- The other group member reviews the PR before it is merged into `main`

**Rules we follow:**
- One branch per Jira issue, created from `main`
- Small, meaningful commits
- An issue moves to **Done** only after its pull request is merged

---

## Scope

### In Scope
Authentication, course search and enrollment, initial assessment, personalized study plans, course roadmap, daily assessments, adaptive difficulty, AI learning assistant, points and streaks, badges, leaderboard, basic community, and notifications.

### Out of Scope (Future Work)
Advanced mentorship management, subscription and payment processing, offline downloads and synchronization, native Android/iOS apps, live video classes, enterprise learning management, and full certification systems.

---

## Project Links

- **Jira Project:** https://aliahmed17005.atlassian.net/jira/software/projects/SCRUM
- **GitHub Repository:** https://github.com/\<your-username\>/\<repo-name\>

---

## License

This project was developed for academic purposes as part of CS4002 at FAST-NUCES.
