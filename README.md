# 📝 ToDo Web App (Go + Gin + HTML/CSS/JS)

A clean, functional ToDo list web application that performs basic **CRUD operations** — Add, View, Update, and Delete tasks. The backend is built using **Go** and the **Gin framework**, while the frontend uses **HTML, CSS, and JavaScript**.

This project is ideal for learning how frontend and backend communicate using REST APIs.

---

## 📸 Homepage Screenshot

![Screenshot](https://raw.githubusercontent.com/kamaljeet-01/CRUD-API/main/Screenshot 2025-07-18 151229.png)

---

## ✨ Features

- ➕ Add task with `Id`, `Task`, and `Done` status
- 🗑️ Delete task using its ID
- ♻️ Update existing task by ID
- 📋 View all tasks in a formatted list
- 🌐 User-friendly interface using vanilla JS + CSS
- ⚡ Real-time interaction using `fetch()` API

---

## 🧾 Project Folder Structure

- todo/
- ├── backend/
- │ ├── main.go # Go server code
- │ ├── go.mod
- │ └── go.sum
- │
- ├── frontend/
- │ ├── index.html # Web interface
- │ ├── style.css # Styling
- │ └── script.js # JavaScript logic
- │
- └── screenshots/
- └── homepage.png # Screenshot of homepage


---

## ⚙️ Tech Stack

| Layer     | Technology       |
|-----------|------------------|
| Backend   | Go, Gin          |
| Frontend  | HTML, CSS, JS    |
| Protocol  | HTTP + JSON      |

---

## 📦 Setup Instructions

### Prerequisites

- Go installed (`go version`)
- A browser (Chrome, Firefox, etc.)

---

### 🛠 Run the Project

1. **Clone the repository**

```bash
git clone https://github.com/kamaljeet-01/CRUD-API.git
cd todo/backend
