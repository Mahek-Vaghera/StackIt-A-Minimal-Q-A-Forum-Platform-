# StackIt – A Minimal Q&A Forum Platform

**StackIt** is a minimalist question-and-answer platform designed for collaborative learning and structured knowledge sharing. It focuses on simplicity, a clean interface, and powerful tools for asking and answering questions in a community setting.

---

## 🚀 Features

### ✅ Core Functionality

- **Ask Questions**
  - Users can ask questions with:
    - A short and descriptive **title**
    - A detailed **description** using a **rich text editor**
    - **Tags** (multi-select input such as `React`, `JWT`, etc.)

- **Answer Questions**
  - Logged-in users can post answers to any question
  - Rich text editor support for formatting

- **Rich Text Editor**
  - Features:
    - Bold, Italic, Strikethrough
    - Numbered and Bullet Lists
    - Emoji insertion
    - Hyperlink and Image upload
    - Text alignment: Left, Center, Right

- **Voting & Accepted Answers**
  - Upvote/downvote answers
  - Question owners can mark an answer as **accepted**

- **Tags System**
  - Tag questions with relevant technologies or topics

- **Notification System**
  - 🔔 Bell icon in top navbar
  - Notify users when:
    - Someone answers their question
    - Someone comments on their answer
    - Someone mentions them using `@username`
  - Dropdown with recent unread notifications

---

## 👥 User Roles & Permissions

| Role   | Permissions |
|--------|-------------|
| Guest  | View all questions and answers |
| User   | Register, log in, post questions/answers, vote |
| Admin  | Moderate content, ban users, send platform-wide messages, download reports |

---

## 🔐 Admin Features

- Reject inappropriate or spam content
- Ban users who violate platform rules
- Manage pending/accepted/cancelled swaps
- Send platform-wide announcements (e.g. downtime, feature updates)
- Download reports (user activity, feedback logs, swap stats)

---

## 🛠️ Tech Stack

| Layer         | Tech                          |
|---------------|-------------------------------|
| Frontend      | React, React Router, Axios    |
| Backend       | Node.js, Express.js           |
| Database      | MongoDB, Mongoose             |
| Auth          | JWT, bcrypt.js                |
| Rich Text     | TipTap or Quill.js            |
| Notifications | Socket.io / Polling           |
| Styling       | Tailwind CSS / CSS Modules    |

---
