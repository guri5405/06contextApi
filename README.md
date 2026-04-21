# 📝 Todo App (React + Context API)

## 🚀 Overview

This is a simple and efficient Todo Application built using React and Context API for global state management. The app allows users to manage daily tasks with features like adding, updating, deleting, and marking tasks as completed. It also uses localStorage to persist data.

---

## ✨ Features

* ➕ Add new todos
* ✏️ Update existing todos
* ❌ Delete todos
* ✅ Mark todos as completed / uncompleted
* 💾 Persistent storage using localStorage
* 🌐 Global state management using Context API (no prop drilling)

---

## 🧠 Tech Stack

* React (Hooks: useState, useEffect)
* Context API (Global State Management)
* Tailwind CSS (for styling)
* JavaScript (ES6+)

---

## 📁 Project Structure

```bash
src/
│
├── components/
│   ├── TodoForm.jsx
│   ├── TodoItem.jsx
│   └── index.js
│
├── contexts/
│   ├── TodoContext.js
│   └── index.js
│
├── App.jsx
└── main.jsx
```

---

## ⚙️ How It Works

* The app uses Context API to manage global state (todos and related functions).
* All CRUD operations (Add, Update, Delete, Toggle) are handled in App.jsx.
* State is shared across components using TodoProvider.
* useEffect is used to:

  * Load todos from localStorage on app start
  * Save todos whenever state updates

---

## 🛠️ Installation & Setup

```bash
# Clone the repository
https://github.com/guri5405/06contextApi.git

# Navigate to project folder
cd 06contextApi

# Install dependencies
npm install

# Run the app
npm run dev
```

---

## 📸 UI Preview

* Clean and minimal UI
* Responsive layout
* Styled using Tailwind CSS

---

## 📌 Future Improvements

* Add filters (All / Completed / Pending)
* Add due dates & reminders
* Drag and drop functionality
* Backend integration (API + Database)
* User authentication

---

## 🤝 Contribution

Contributions are welcome! Feel free to fork the repo and submit a pull request.

---

## 📄 License

This project is open-source and available under the MIT License.
