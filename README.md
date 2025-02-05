# Task Management System

![PHP](https://img.shields.io/badge/PHP-8.0%2B-blue)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3-purple)
![MySQL](https://img.shields.io/badge/MySQL-8.0-orange)
![License](https://img.shields.io/badge/License-MIT-green)

A simple yet powerful **Task Management System** built with PHP and MySQL. This project allows users to perform CRUD (Create, Read, Update, Delete) operations on tasks, with additional features like task status tracking, search functionality, and a responsive Bootstrap-based UI.

---

## Features

- **Create Tasks**: Add new tasks with a title, description, due date, and status.
- **View Tasks**: Display all tasks in a clean, responsive table.
- **Edit Tasks**: Update existing tasks with new information.
- **Delete Tasks**: Remove tasks from the system.
- **Task Status**: Track task progress with status options: `Pending`, `In Progress`, and `Completed`.
- **Search Functionality**: Search for tasks by title or description.
- **Responsive Design**: Built with Bootstrap for a mobile-friendly experience.
- **Validation**: Server-side and client-side form validation.

---

## Screenshot

![image](https://github.com/user-attachments/assets/f1faa5d3-9e1a-4d59-aa9c-af46c12190c4)


---

## Installation

Follow these steps to set up the project locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/task-management-system.git
   cd task-management-system
2. **Set Up the Database**:
- Create a MySQL database named task_manager.
- Import the task_manager.sql file located in the database folder:
   ```bash
   mysql -u your_username -p task_manager < database/task_manager.sql
3. **Configure Database Connection**:
- Open **config/database.php** and update the database credentials:
   ```bash
   $host = 'localhost';
   $dbname = 'task_manager';
   $username = 'your_username'; // Replace with your MySQL username
   $password = 'your_password'; // Replace with your MySQL password
4. **Run the Application**:
- Start a local server (e.g., XAMPP, WAMP, or Laravel Homestead).
- Open the project in your browser:
   ```bash
   http://localhost/task-management-system

---

## Usage

1. **Home Page**:
- View all tasks in a table.
- Use the search bar to filter tasks by title or description.
2. **Create a Task**:
- Click the "Add New Task" button.
- Fill out the form with task details (title, description, due date, and status).
- Submit the form to add the task.
3. **Edit a Task**:
- Click the "Edit" button next to a task.
- Update the task details in the form.
- Submit the form to save changes.
4. **Delete a Task**:
- Click the "Delete" button next to a task.
- Confirm the deletion to remove the task permanently.

---

## Technologies Used

- **PHP**: Backend logic and database interaction.

- **MySQL**: Database management.

- **Bootstrap**: Frontend styling and responsiveness.

- **HTML/CSS**: Structure and custom styling.

- **JavaScript**: Client-side validation (optional).

---

## Folder Structure

     task-management-system/
     ├── index.php            # Entry point (list all tasks)
     ├── create.php           # Form to create a new task
     ├── edit.php             # Form to edit an existing task
     ├── delete.php           # Script to delete a task
     ├── config/
     │   └── database.php     # Database connection settings
     ├── includes/
     │   ├── header.php       # Common header (navigation bar)
     │   ├── footer.php       # Common footer
     │   └── functions.php    # Helper functions (e.g., database queries)
     ├── assets/
     │   ├── css/
     │   │   └── styles.css   # Custom CSS for styling
     │   └── js/
     │       └── script.js    # Custom JavaScript (e.g., form validation)
     ├── database/
     │   └── task_manager.sql # Database schema and sample data
     └── README.md            # Project documentation

---

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bugfix:

        git checkout -b feature/your-feature-name
3. Commit your changes:

       git commit -m "Add your message here"
4. Push to the branch:

       git push origin feature/your-feature-name
6. Open a pull request and describe your changes.

---

## License

This project is licensed under the **MIT License**. See the LICENSE file for details.

---

## Acknowledgments

- **Bootstrap** for the responsive design.
- **PHP** and **MySQL** for backend functionality.
- **GitHub** for hosting the project.

