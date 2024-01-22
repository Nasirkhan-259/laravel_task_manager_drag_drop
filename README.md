# Simple Task Manager

This Laravel project is a simple task manager focused on project-based tasks. It features a drag-and-drop functionality to reorder tasks easily.

## Installation

Follow these steps to set up the project:

1. **Clone the Repository:** Clone this repository to your local machine.

2. **Set Up Environment File:** Copy `.env.example` file to a new file named `.env`. Update your database information in the `.env` file.

3. **Install Dependencies:** Run `composer update` to install required dependencies.

4. **Generate Application Key:** Run `php artisan key:generate` to set your application key.

5. **Run Migrations:** Execute `php artisan migrate` to create the database schema.

6. **Start the Server:** Use `php artisan serve` to start the Laravel development server.

7. **Visit the Application:** Open your browser and visit `localhost:8000` to view the application.

## Features

- **Task Management:** Create, edit, and delete tasks.
- **Project-Based:** Organize tasks by projects.
- **Drag and Drop:** Reorder tasks with an intuitive drag-and-drop interface.
