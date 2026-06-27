# TaskFlow

**A lightweight, fully offline web application for personal task and todo management.**

TaskFlow is a clean, modern, and professional Progressive Web App (PWA) designed for managing daily tasks. It works seamlessly on both Android and desktop browsers without requiring any installation or account.

**Live Demo:** https://gemcancers-debug.github.io/taskflow

**Repository:** https://github.com/gemcancers-debug/taskflow

---

## How to Use

### 1. Adding a New Task
- Enter the task title in the first field.
- Add an optional description.
- Select the priority level (High / Medium / Low).
- Optionally set a due date.
- Click the **"Add Task"** button.

### 2. Managing Tasks
- Click the checkbox next to a task to mark it as completed.
- Use the search bar to quickly find specific tasks.
- Use the filter buttons (**All**, **Active**, **Completed**) to view tasks by status.
- Click the trash icon to delete a task.

### 3. Statistics & Progress
The dashboard at the top automatically displays:
- Total number of tasks
- Number of active tasks
- Number of completed tasks
- Overall progress percentage with a visual bar

### 4. Additional Features
- **Theme Toggle**: Switch between Dark and Light mode.
- **Export Data**: Download all your tasks as a JSON file.
- **Import Data**: Upload a previously exported JSON file to restore tasks.
- **Clear All**: Remove all tasks at once (with confirmation).

---

## Rules & Technical Notes

- All data is stored locally in your browser using `localStorage`. No data is sent to any server.
- The application works completely offline after the first visit.
- Tasks are saved automatically and persist even after closing the browser.
- The app is fully responsive and optimized for both mobile (Android) and desktop use.
- You can install TaskFlow as a Progressive Web App (PWA) on Android: Open the site in Chrome, then tap the "Install" icon in the address bar.
- No login, registration, or internet connection is required after the initial load.

---

**Developed by Hamed Farifteh**