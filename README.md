# Quiz & Learn App

Welcome to the **Quiz & Learn** application! This project is a web-based quiz platform where users can select a topic and test their knowledge. The app is designed with Django for the backend and uses TailwindCSS for styling, ensuring both functionality and a sleek user interface.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)

## Features

- User authentication (Login & Sign Up)
- Topic selection for quizzes
- Dynamic quiz generation with multiple topics
- TailwindCSS-based styling for a responsive design
- Smooth hover and button animations
- Clear form validation messages
- Background image with overlay for visual clarity

## Technologies Used

- **Backend:** Django
- **Frontend:** HTML, TailwindCSS, Bootstrap Icons
- **Interactivity:** HTMX
- **Version Control:** Git & GitHub

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/AdamTa05/Quiz-Learn.git
    ```
2. Navigate into the project directory:
    ```bash
    cd Quiz-App
    ```
3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Set up the database:
    ```bash
    python manage.py migrate
    ```
5. Run the development server:
    ```bash
    python manage.py runserver
    ```

## Usage

1. Open your web browser and navigate to `http://127.0.0.1:8000`.
2. Register or log in if you already have an account.
3. Choose a topic from the list to start your quiz.
4. Answer questions and check your results!

## Screenshot

![Quiz App](./static/images/Quiz-Screenshot.jpeg)           

---

Feel free to fork this project, submit issues, and contribute!

