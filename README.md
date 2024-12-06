# laravel-react-todo
A comprehensive Todo app built with [Laravel](https://laravel.com) for the backend and [ReactJS](https://reactjs.org) for the frontend. This app allows users to manage their tasks efficiently with features like user authentication, task categorization, priority levels, and due dates.

# Getting Started

Getting Started
-Follow these steps to set up and run the project:

Clone the project by running the command below:

bash
`git clone https://github.com/nabidam/laravel-react-todo.git`
`cd laravel-react-todo`

Backend Setup

1-Navigate to the Backend Directory:

bash
`cd todo-backend`

2-Install Composer Dependencies:

bash
`composer install`

3-Create the .env File by renaming `.env.example` to `.env` or :

bash
`cp .env.example .env`

4-Generate the Application Key:

bash
`php artisan key:generate`

5-Configure the Database: Update your .env file with the database details.

6-Run the Migrations:

`php artisan migrate`

then start the application:

`php artisan serve`

Access the Application

and visit http://localhost:8000 to see the application.

# Built with
* [Laravel](https://laravel.com)
* [ReactJS](https://reactjs.org)
* [Material UI](https://material-ui.com)
* [Font Awesome](https://fontawesome.com)

