# TaskFlow Android Demo (Kotlin, MVVM)

A fully interactive Android demo app built to demonstrate production-level app structure, clean architecture, and feature implementation using Kotlin.

---

## Overview

TaskFlow is a task management demo app designed to showcase:

- Clean MVVM architecture
- Structured UI/UX
- Full CRUD functionality
- Local data storage with Room
- API integration with Retrofit
- Search and filtering system

This project is intended as a portfolio/demo piece to demonstrate real-world Android development practices.

---

## Features

### Dashboard
- Live task statistics (Total, In Progress, Done)
- Task list with priority badges and status indicators

### Task Detail
- View full task information
- Update task status
- Delete tasks

### Add / Edit Task
- Create new tasks with title, description, priority, and due date
- Edit existing tasks

### Search & Filter
- Search by title or description
- Filter by status and priority

### Architecture View
- Includes MVVM structure overview
- Clear package organization
- Demonstrates scalable project setup

---

## Tech Stack

- **Language:** Kotlin
- **Architecture:** MVVM
- **UI:** XML / RecyclerView
- **Database:** Room
- **Networking:** Retrofit
- **Async Handling:** Coroutines / LiveData

---

## Project Structure

```
com.demo.taskflow
│
├── ui/
├── viewmodel/
├── repository/
├── model/
├── network/
├── database/
```

---

## Demo Purpose

This project demonstrates:

- Clean and maintainable Android code
- Proper separation of concerns
- Scalable architecture for team environments
- Real-world feature implementation

---

## How to Run

1. Clone the repository
2. Open in Android Studio
3. Build and run on emulator or device

---

## Author

Muhammad Usman Shah Din  
Android Developer | Full Stack Developer

---

## Note

This is a demo project created to showcase development approach and code structure. It can be extended into a production-ready application with backend integration and deployment setup.
