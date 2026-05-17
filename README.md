# 📝 To-Do List

A clean and minimal To-Do List web app built with HTML, CSS, and vanilla JavaScript. Tasks are saved in localStorage so they persist even after closing the browser.

---

## 📸 Preview

![To-Do List Preview](Preview.png)

---

## ✨ Features

- Add tasks to your list
- Click a task to mark it as completed
- Delete individual tasks with the × button
- Tasks saved with localStorage — no data lost on refresh
- Clean responsive UI with a smooth gradient background

---

## 🚀 Getting Started

### Option 1 — Live Demo
👉 [Try it here](https://pranav-gt.github.io/TO-DO-List/) *(update this link after deploying)*

### Option 2 — Run Locally

```bash
git clone https://github.com/Pranav-GT/TO-DO-List.git
cd TO-DO-List
```

Then just open `index.html` in your browser — no server or install needed.

---

## 📁 Project Structure

```
TO-DO-List/
├── index.html       # App structure and layout
├── style.css        # Styling and animations
├── main.js          # Task logic and localStorage handling
├── images/
│   ├── icon.png
│   ├── checked.png
│   └── unchecked.png
└── README.md
```

---

## 🔧 How It Works

| Component | Description |
|---|---|
| `addTask()` | Creates a new `<li>` element and appends it to the list |
| Click on task | Toggles the `checked` class — strikethrough + filled icon |
| Click on × | Removes the task from the DOM |
| `saveData()` | Saves the current list HTML to localStorage |
| `showTask()` | Loads saved tasks from localStorage on page load |

---

## 🛠️ Built With

- HTML5
- CSS3
- JavaScript (Vanilla)
- Google Fonts — Poppins

---

## 📄 License

MIT — free to use, modify, and distribute.
