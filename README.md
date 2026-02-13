# Task Status Management Platform

## Overview

Task State Manager is a client-side task management application that allows users to create, edit, delete, and update the completion status of tasks. The app includes dynamic filtering to view all, pending, or completed tasks and updates the interface in real time based on user interactions.
This project demonstrates structured state handling using a controller-based architecture.

## Features

- Add new tasks
- Edit existing tasks
- Delete tasks
- Mark tasks as completed or pending
- Filter tasks by status:
  - All
  - Pending
  - Completed
- Real-time UI updates
- Responsive design

## Technologies Used

- HTML5  
- CSS3  
- Bootstrap 5  
- JavaScript  
- AngularJS (1.x)

## Architecture

The application follows a client-side state management approach:
- Tasks are stored in an array.
- Each task contains:
  - `text`
  - `completed` (boolean state)
- A controller manages:
  - State transitions
  - Filtering logic
  - CRUD operations
- UI updates dynamically through data binding.
- 
## How to Run

1. Download or clone the repository.
2. Open the `index.html` file in a web browser.
3. Start managing tasks.
No backend or additional setup is required.

## Purpose

This project demonstrates:
- Client-side task state management  
- Dynamic UI updates using data binding  
- Structured controller-based application design  
- Basic CRUD operations implementation  

---

