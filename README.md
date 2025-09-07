# Django 5 Movie Catalog Project

This repository contains a comprehensive movie catalog and review web application built with **Django 5**. It is the final project developed by following the practical examples and lessons from the book ***"Django 5 for the Impatient"***.

This application serves as a hands-on demonstration of modern Django development practices, showcasing everything from initial project setup to implementing key features like user authentication and database interactions.

---

## Key Features

* **Movie Listings:** Browse a dynamic catalog of movies, each with detailed information such as title, release year, director, and a synopsis.
* **User Authentication:** A complete and secure user management system including registration, login, and logout functionality using Django's built-in authentication.
* **Review System:** Authenticated users can post, view, and manage their own ratings and reviews for movies in the catalog.
* **Admin Panel:** Utilizes Django's powerful built-in admin interface for easy and efficient content management (adding movies, managing users, etc.).
* **Class-Based Views (CBVs):** Implements modern, scalable, and reusable view logic using Django's class-based views.
* **Static File Handling:** Demonstrates proper configuration and management of static assets like CSS and images.

---

## Technology Stack

* **Backend:** Django 5
* **Database:** SQLite (default for development)
* **Frontend:** HTML, CSS (with Django Template Language)

---

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

* Python 3.10+
* Pip

### Installation

1.  Clone the repository:
    ```sh
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    cd your-repo-name
    ```
2.  Create and activate a virtual environment:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```
3.  Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```
4.  Apply the database migrations:
    ```sh
    python manage.py migrate
    ```
5.  Create a superuser to access the admin panel:
    ```sh
    python manage.py createsuperuser
    ```
6.  Run the development server:
    ```sh
    python manage.py runserver
    ```

The application will be available at `http://127.0.0.1:8000`.
