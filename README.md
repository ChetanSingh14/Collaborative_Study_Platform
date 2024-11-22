# Collaborative Study Platform

## Project Overview
The **Collaborative Study Platform** is a full-stack web application designed for students and educators to collaborate and share educational resources. This platform is divided into two main components:

- **Backend**: Built with Node.js and Express.js for APIs, database handling, and server-side logic.
- **Frontend**: Created with React.js to provide an interactive and user-friendly interface.

---

## Folder Structure

```plaintext
Collaborative_Study_Platform
├── Backend
│   ├── Controllers       # Handles business logic and API request responses
│   ├── Models            # Database schema and models
│   ├── Routes            # API routes for various functionalities
│   ├── db.js             # MongoDB connection configuration
│   ├── index.js          # Entry point for the backend server
│   ├── package.json      # Backend dependencies and scripts
│   ├── package-lock.json # Backend dependency lockfile
│
├── Frontend
│   ├── node_modules      # Frontend dependencies
│   ├── public            # Static assets
│   ├── src               # React.js components and logic
│   ├── package.json      # Frontend dependencies and scripts
│   ├── package-lock.json # Frontend dependency lockfile
│   ├── .gitignore        # Ignored files for Git
│   ├── README.md         # Frontend-specific documentation
│
├── .gitignore            # Ignored files for Git
├── README.md             # Main project documentation
```

## Features

### Current Features
1. **User Authentication**
   - Secure sign-up and login for educators and students.
   - Passwords are stored securely using hashing.

2. **Course Management**
   - Educators can create and manage courses.
   - Students can enroll in courses and view assigned resources.

3. **Resource Sharing**
   - Upload and manage notes, PDFs, presentations, and other materials.
   - Download resources by course.

4. **Real-time Collaboration**
   - Interactive discussion forums and chats for students and educators.

5. **Personalized Dashboard**
   - Shows enrolled courses, uploaded resources, and pending tasks.

---

## Proposed Features

1. **Virtual Whiteboard**
   - Enable brainstorming and diagram sharing in real-time.

2. **Quiz Management**
   - Educators can create quizzes; automatic grading and feedback generation.

3. **Push Notifications**
   - Notify students about deadlines, updates, and announcements.

4. **Group Projects**
   - Create project groups for collaborative tasks with progress tracking.

5. **Progress Tracking**
   - Visualize students' performance and course completion rates.

6. **Video Conferencing Integration**
   - Include live classes and video tutorials for an immersive experience.

7. **Dark Mode**
   - Add a theme toggle for better accessibility and user experience.

---

## How to Run the Project

### Backend
1. Navigate to the `Backend` directory:
   ```bash
   cd Backend
