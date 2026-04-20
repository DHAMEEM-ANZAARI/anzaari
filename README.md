# Task Manager

A lightweight, single-file Task Manager web application built with plain HTML, CSS, and JavaScript. No frameworks, no backend, no dependencies — just open the file in a browser and it works.

## Features

- **User Registration** — Create an account with email and password
- **User Login** — Secure login with credential validation
- **Forgot Password** — Reset your password using your registered email
- **Add Tasks** — Create new tasks instantly (also supports Enter key)
- **View Tasks** — See all your tasks in a clean list
- **Mark Complete** — Check off tasks with a checkbox (strikethrough effect)
- **Delete Tasks** — Remove individual tasks with a Delete button
- **Logout** — Safely end your session

---

## Tech Stack

| Layer      | Technology          |
|------------|---------------------|
| Markup     | HTML5               |
| Styling    | CSS3                |
| Logic      | JavaScript          |
| Storage    | In-memory (runtime) |
| Hosting    | GitHub Pages        |

> **Note:** Data is stored in-memory and resets on page refresh. There is no database or persistent backend.

---

## Project Structure

```
task-manager/
└── index.html       # Entire app — HTML + CSS + JS in one file
└── README.md        # Project documentation
```

---

## Getting Started

### Option 1 — Open Locally

1. Download `task-manager.html`
2. Double-click to open it in any browser
3. No installation or server needed

## How to Use

### Register
1. Enter your email and password in the **Register** box
2. Click **Register**
3. A success message confirms your account is created

### Login
1. Enter your registered email and password in the **Login** box
2. Click **Login**
3. You will be taken to the Task Manager dashboard

### Forgot Password
1. On the Login page, click **Forgot Password?**
2. Enter your registered email
3. Enter and confirm your new password
4. Click **Reset Password** — you'll be redirected to Login automatically

### Managing Tasks
| Action          | How                                      |
|-----------------|------------------------------------------|
| Add a task      | Type in the input box → click **Add Task** or press **Enter** |
| View tasks      | Click **View Tasks** or add a task (auto-refreshes) |
| Complete a task | Click the checkbox next to the task      |
| Delete a task   | Click the **Delete** button on the task  |
| Logout          | Click the **Logout** button at the bottom |


## Limitations

- Data is **not persistent** — refreshing the page clears all users and tasks
- No real email verification for registration or password reset
- Designed as a frontend-only demo; not suitable for production use without a backend

---

## License

This project is open source and free to use for learning and personal projects.
