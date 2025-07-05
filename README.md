📝 Notes App
A simple browser-based Notes App that allows you to create, edit, and delete notes — with automatic saving using localStorage.

📸 Demo
Create editable notes. Add multiple notes. Delete them. Everything stays saved even after page refresh!

🚀 Features
🧠 Persistent Storage — All notes are saved to localStorage

🆕 Create Notes — Click a button to add a new note

✏️ Editable Notes — Click on any note to edit it directly

🗑️ Delete Notes — Click the trash icon to remove a note

⏎ Multiline Support — Pressing Enter adds a new line instead of submitting

📁 Project Structure
pgsql
Copy
Edit
project/
│
├── index.html
├── style.css
├── script.js      ← (This is the code you shared)
├── Delete-PNG-Picture.png
└── README.md
💻 How to Use
Download or Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/notes-app.git
Open index.html in your browser.

Click the "Create Note" button to add a new note.

Type your note directly. It saves automatically as you type.

Click the delete icon to remove a note.

🛠️ Technologies Used
HTML

CSS

JavaScript

localStorage for saving data

📦 Local Storage Format
All notes are saved as innerHTML in localStorage under the key "notes".



🖼️ Assets
Make sure you include the delete image in your project directory:

Delete-PNG-Picture.png — used as the trash icon.

🔒 Disclaimer
This app stores your notes in your browser only (using localStorage). It does not sync across devices or save to a cloud server.

📃 License
MIT License — free to use and modify.

