# TaskManager
TaskManager is a powerful and intuitive tool designed to help you stay organized and manage your daily activities with ease. Whether you're tracking work projects, personal goals, or household chores, TaskManager offers a comprehensive set of features to keep you on top of your tasks.

![Python](https://img.shields.io/badge/Language-Python3.9-green)
![PyQt-Designer](https://img.shields.io/badge/UI-PyQt_Designer-orange)
![Pandas](https://img.shields.io/badge/Library-Pandas-red)

## Preview

## Features

### Task Management
- **Create Tasks**: Easily add new tasks for your daily activities with detailed descriptions and deadlines.
- **Update Task Status**: Change the status of your tasks to reflect their current progress. Status options include: Not Started, In Progress, Pending, Completed, and Backlog.
- **View Tasks**: Access a list of all your tasks along with their current statuses in a clean, user-friendly interface.

### Advanced Filtering and Sorting
- **Filter Tasks**: Quickly filter tasks based on their status to focus on what's important right now.
- **Sort Tasks**: Organize your tasks by unique ID, task name, description, creation date, start date, completion date, or the number of days left until the deadline.

### User Interface
- **Intuitive UI**: Navigate through your tasks effortlessly with our easy-to-use interface designed to enhance your productivity and task management experience.

## Installation

1. Clone the repository:
   
   `git clone https://github.com/your-username/TaskManager.git`

2. Install dependency modules

    `pip3 install -r requirements.txt`

 
## How to execute code
1. Execute below command to run the code

     `python task_manager.py`

## Additional Details
1. Execute below command if you want to create a executable file for this program

    `pyinstaller -n "Task Planner" --add-data="task_manager_home_page.ui;." --noconsole --onefile task_manager.py`
