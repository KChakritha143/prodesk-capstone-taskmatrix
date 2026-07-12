# TaskMatrix

## Project Overview

TaskMatrix is a modern Agile Project Management platform designed for software teams to efficiently plan, organize, track, and manage projects. Inspired by tools such as Jira, Asana, and Trello, TaskMatrix provides a centralized workspace where teams can collaborate, assign tasks, monitor project progress, manage deadlines, and improve productivity.

This project is being developed as a Capstone Project under the Prodesk Residency Program.

---

## Designated Track

**Full Stack Development**

---

## Problem Statement

Managing projects across multiple team members can become challenging without a centralized platform. Teams often face issues with task tracking, project visibility, collaboration, communication, and deadline management.

TaskMatrix aims to provide a scalable and user-friendly solution that simplifies project planning and execution.

---

## Solution

TaskMatrix provides an Agile project management environment where users can:

- Create and manage projects
- Assign tasks to team members
- Track progress using Kanban boards
- Manage priorities and deadlines
- Collaborate through comments and activity feeds
- Monitor project performance

---

## Tech Stack

### Frontend

- Next.js
- Tailwind CSS
- Shadcn UI
- Zustand

### Backend

- Node.js
- Express.js

### Database

- MongoDB Atlas

### Authentication

- JWT (JSON Web Token)

### Deployment

- Vercel (Frontend)
- Render (Backend)
- MongoDB Atlas (Database)

---

## Core Features

### Authentication & Authorization

- User Registration
- User Login
- JWT Authentication
- Role-Based Access Control (RBAC)

### Project Management

- Create Project
- Update Project
- Delete Project
- View Projects

### Task Management

- Create Task
- Update Task
- Delete Task
- Assign Tasks
- Due Date Management
- Priority Management

### Kanban Board

- Backlog
- To Do
- In Progress
- Review
- Done
- Drag-and-Drop Task Movement

### Team Collaboration

- Comments
- Activity Feed
- Team Member Management

### Dashboard

- Project Overview
- Task Statistics
- Recent Activities

### Notifications

- Assignment Alerts
- Task Updates
- Project Notifications

### File Attachments

- Upload Files
- Download Files

---

## User Roles

### Admin

- Manage Users
- Manage Projects
- Monitor Activities

### Project Manager

- Create Projects
- Assign Tasks
- Manage Team Members
- Track Progress

### Team Member

- View Assigned Tasks
- Update Task Status
- Add Comments

---

## UI/UX Wireframes

### Figma Design

https://www.figma.com/design/aEGzAIjEwnSxMyi5A2zuX3/task-matrix-UI-design?node-id=3-2&p=f&t=s0Ssf3qaJ6Twatsz-0

### Designed Screens

1. Authentication Screen
2. Dashboard Screen
3. Task Details Screen

---

## Database Architecture

### Collections

- Users
- Projects
- Project Members
- Tasks
- Comments
- Notifications
- Activity Logs
- Attachments
- Labels
- Task Labels

---

## Entity Relationship Diagram

<img width="1048" height="892" alt="Untitled (1)" src="https://github.com/user-attachments/assets/16dafca0-3222-4a5e-96a9-ee83fbee715f" />

---

## Planned API Endpoints

### Authentication

```http
POST /api/auth/register
POST /api/auth/login
```

### Projects

```http
GET    /api/projects
GET    /api/projects/:id
POST   /api/projects
PUT    /api/projects/:id
DELETE /api/projects/:id
```

### Tasks

```http
GET    /api/tasks
GET    /api/tasks/:id
POST   /api/tasks
PUT    /api/tasks/:id
DELETE /api/tasks/:id
```

### Comments

```http
GET    /api/comments
POST   /api/comments
DELETE /api/comments/:id
```

### Notifications

```http
GET /api/notifications
PUT /api/notifications/:id
```

---

## Development Roadmap

### Sprint 13

- Project Planning
- Documentation
- Wireframes
- Database Design
- ERD Creation

### Sprint 14

- Authentication Module
- User Management
- Project CRUD

### Sprint 15

- Task CRUD
- Kanban Board
- Team Collaboration

### Sprint 16

- Notifications
- Attachments
- Activity Feed

### Sprint 17

- Testing
- Deployment
- Final Presentation

---

## Future Enhancements

- AI Task Suggestions
- AI Sprint Planning Assistant
- AI Project Summary Generator
- Email Notifications
- Team Performance Analytics
- Calendar Integration
- Dark Mode Support

---

## Prompts Documentation

All AI-assisted prompts used during planning and development are documented in:

```text
Prompts.md
```

---

## Repository Structure

```text
prodesk-capstone-taskmatrix
│
├── README.md
├── Prompts.md
├── docs
│   └── erd.png
│
├── frontend
└── backend
```
