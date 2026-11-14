TaskFlow – To-Do List App

A clean, minimal to-do list app for adding, completing, and deleting tasks. Built with plain HTML, CSS, and JavaScript, with no frameworks or dependencies.

Live Demo

https://6af81e77250672cb9ee69204--taskflowltodoist.netlify.app/

Features
Add tasks with the ADD + button or by pressing Enter
Mark tasks as complete or incomplete by clicking the circle or the task text
Completed tasks get an orange check and a strikethrough
Delete tasks with the trash icon
Empty-state message when there are no tasks
Starts with an empty list every time the page is opened
Responsive layout that works on desktop and mobile
Tech Stack
HTML5
CSS3 (flexbox, CSS variables)
Vanilla JavaScript (ES6)
Getting Started
Clone the repository:
bash
git clone <your-repo-url>
Open the project folder:
bash
cd <your-repo-folder>
Open index.html in your browser. No build step or installation is needed.
Project Structure
.
├── index.html   # Markup, styles, and app logic
└── README.md
How It Works

Tasks are stored in a JavaScript array in memory. Each task has an id, text, and done flag. Every add, toggle, or delete updates the array and re-renders the list. Because nothing is saved to storage, the list resets when the page is reloaded.

Possible Improvements
Save tasks with localStorage
Edit existing tasks
Filter by All / Active / Completed
Drag-and-drop reordering
License

This project is open source and available under the MIT License.
