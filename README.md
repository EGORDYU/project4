## Technologies Used

Django (Python web framework)
React (JavaScript library for building user interfaces)
PostgreSQL (Relational database management system)
Django REST Framework (API framework for Django)
React Router (Library for handling navigation in React)
Axios (HTTP client for making API requests)
JWT (JSON Web Tokens for authentication)
HTML/CSS (Frontend design and styling)
Git (Version control)

## Description
The DR SC2 Coaching Website is a web application that provides StarCraft II coaching services. The application allows users to create an account, log in, and access various features such as leaving comments and viewing build orders, as well as eventually scheduling sessions with a calendar API.

The backend of the application is built using Django, a powerful Python web framework. Django provides a robust and scalable foundation for handling user authentication, managing the database, and serving API endpoints. PostgreSQL is used as the database management system to store user information, comments, and build orders.

The frontend of the application is built using React, a popular JavaScript library for building user interfaces. React Router is used for handling client-side routing, allowing seamless navigation between different pages of the application. Axios is used for making HTTP requests to the backend API, enabling data retrieval and manipulation.

## User Stories

As a user, I want to be able to create an account and log in to the website.
As a user, I want to be able to view a list of build orders for StarCraft II.
As a user, I want to be able to leave comments on build orders.
As a user, I want to be able to filter build orders based on specific criteria (e.g., race, difficulty).


## User Flow

The user visits the website and is presented with a login/signup page.
The user can create a new account or log in using existing credentials.
Upon successful authentication, the user is redirected to the build order page.
The user can browse through the list of available build orders.
The user can click on a build order to view more details and comments.
The user can leave comments on the build order page.
The user can schedule a session with a calendar API.
The user can log out to end the session.
