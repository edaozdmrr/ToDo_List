# ToDo_List
📌 To-Do List with Calendar

📝 Project Description
This is a simple and user-friendly To-Do List application with calendar support.
Users can add tasks with a specific date and custom text color, mark them as completed, and delete them. All tasks are saved locally and persist between sessions.

🚀 Features

📆 Calendar Integration: Assign a due date to each task using a calendar picker.

🎨 Custom Colors: Choose a custom font color for each task.

✅ Mark as Completed: Easily mark tasks as done.

🗑️ Delete Tasks: Remove selected tasks from the list.

💾 Persistent Storage: Tasks are stored in tasks_with_dates.json and reloaded automatically on startup.

🛠️ Technologies Used
Python 3

tkinter – for the graphical user interface

tkcalendar – for the calendar widget

json – to store and load task data

colorchooser – for selecting custom task colors

📥 Installation & Setup

1- Clone this repository or download the ZIP:
git clone https://github.com/yourusername/todo-calendar-app.git
cd todo-calendar-app

2- Install required dependencies:
pip install tkcalendar

3- Run the app:
python todolist.py

📂 Project Structure
todo-calendar-app/

│

├── todolist.py

├── tasks_with_dates.json

└── README.md 
💡 Notes
All tasks are saved automatically after changes.

The app loads previously saved tasks on startup.

If no color is selected, the default color is black.
