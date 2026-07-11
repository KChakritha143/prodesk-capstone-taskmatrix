# TaskMatrix

## Project Overview

TaskMatrix is a modern Agile Project Management platform designed to help software teams plan, organize, track, and manage projects efficiently. Inspired by tools like Jira, Asana, and Trello, the platform provides a centralized workspace where teams can collaborate, monitor progress, manage deadlines, and streamline workflows.

This project is being developed as a Capstone Project under the Prodesk Residency Program.

---

## Designated Track

**Full Stack Development**

---

## Problem Statement

Managing projects across multiple team members can become challenging without a centralized system. Teams often struggle with task tracking, project visibility, deadline management, and collaboration. Existing solutions may be expensive or overly complex for smaller teams.

TaskMatrix aims to provide a simple, scalable, and user-friendly project management platform that enables teams to organize work efficiently and improve productivity.

---

## Solution

TaskMatrix provides an intuitive project management environment where users can create projects, assign tasks, track progress through Kanban boards, manage priorities and deadlines, and collaborate with team members. The platform offers role-based access control and activity tracking to ensure transparency across the project lifecycle.

---

## Core Features

### Authentication & Authorization

* User Registration
* User Login
* Secure Authentication using JWT
* Role-Based Access Control (RBAC)

### Project Management

* Create Projects
* View Projects
* Update Project Details
* Delete Projects

### Task Management

* Create Tasks
* Edit Tasks
* Delete Tasks
* Assign Tasks to Team Members
* Set Due Dates
* Set Task Priorities

### Kanban Board

* To Do
* In Progress
* Review
* Done
* Drag-and-Drop Task Movement

### Team Collaboration

* Task Comments
* Activity Feed
* Team Member Management

### Dashboard

* Project Overview
* Task Statistics
* Recent Activities
* Productivity Insights

---

## User Roles

### Admin

* Manage Users
* Manage Projects
* View All Activities

### Project Manager

* Create and Manage Projects
* Assign Tasks
* Monitor Team Progress

### Team Member

* View Assigned Tasks
* Update Task Status
* Add Comments

---

## Tech Stack

### Frontend

* Next.js
* Tailwind CSS
* Shadcn UI
* Zustand

### Backend

* Node.js
* Express.js

### Database

* MongoDB Atlas

### Authentication

* JWT (JSON Web Token)

### Deployment

* Vercel (Frontend)
* Render (Backend)
* MongoDB Atlas (Database)

---

## Database Architecture

### Users

* id
* name
* email
* password
* role

### Projects

* id
* name
* description
* ownerId
* createdAt

### Tasks

* id
* title
* description
* status
* priority
* assignedTo
* projectId
* dueDate

### Comments

* id
* taskId
* userId
* message

### Activities

* id
* userId
* taskId
* action
* timestamp

---

## Planned API Endpoints

### Authentication

* POST /api/auth/register
* POST /api/auth/login

### Projects

* GET /api/projects
* POST /api/projects
* PUT /api/projects/:id
* DELETE /api/projects/:id

### Tasks

* GET /api/tasks
* POST /api/tasks
* PUT /api/tasks/:id
* DELETE /api/tasks/:id

### Comments

* GET /api/comments
* POST /api/comments

---

## Wireframes (Figma)

Figma Design Link:

https://www.figma.com/design/aEGzAIjEwnSxMyi5A2zuX3/task-matrix-UI-design?node-id=3-2&p=f&t=s0Ssf3qaJ6Twatsz-0

---

## System Architecture Diagram

ERD Diagram:

**To be added after architecture design completion**

---

## Development Roadmap

### Sprint 13

* Project Planning
* PRD Documentation
* UI/UX Wireframes
* Database Design
* Architecture Diagram

### Sprint 14

* MVP Development
* Authentication
* Project CRUD
* Task CRUD

### Sprint 15

* Kanban Board
* Role Management
* Team Collaboration

### Sprint 16

* AI Integration
* UI/UX Improvements
* Advanced Features

### Sprint 17

* Testing
* Deployment
* Final Presentation

---

## Future Enhancements

* AI Task Suggestions
* AI Project Summary Generator
* Real-Time Notifications
* Email Alerts
* Team Performance Analytics
* Calendar Integration
* Dark Mode Support

---

## Prompts Documentation

All AI-assisted planning prompts used during the project lifecycle are documented in the `Prompts.md` file.

---

