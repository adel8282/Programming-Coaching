# APU Programming Café Management System

A Python-based management system for the APU Programming Café, designed to streamline the administration of supplementary programming coaching classes across all academic levels — from Foundation to Degree programmes.

## Overview

The system coordinates coaching enrolment, trainer assignment, student payments, and class scheduling across three proficiency levels. Four user roles interact with the platform, each with distinct permissions and responsibilities.

## User Roles

| Role | Responsibilities |
|---|---|
| Admin | Manages the system, oversees all operations, and handles user accounts |
| Trainer | Conducts coaching sessions and manages assigned students |
| Lecturer | Identifies students requiring extra support and enrols them in appropriate classes |
| Student | Registers for coaching, completes payment, and attends sessions |

## Coaching Structure

- **Levels:** Beginner, Intermediate, Advanced
- **Duration:** 3 months per class
- **Enrolment:** By lecturer referral or student self-request
- **Access:** Attendance is restricted to students who have completed payment
- **Fees:** Applied per module and class level

## Features

- Role-based access control with four distinct user types
- Class enrolment management by lecturers and student self-registration
- Payment processing and attendance gating
- Trainer assignment to classes and student cohorts
- Multi-level class scheduling (Beginner / Intermediate / Advanced)
- Persistent data storage via flat file I/O

## Tech Stack

| Category | Details |
|---|---|
| Language | Python |
| Paradigm | Object-Oriented Programming |
| Persistence | File I/O |

## Run

```bash
python main.py
```

## Project Structure

```
Programming-Coaching/
├── main.py       # Full application source
├── files.txt     # Persistent data store
└── README.md
```
