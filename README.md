# django_vue_challenge
Django+Vue cyber security challenge (A03:2021-Injection, A07:2021-Identification and Authentication Failures )

# [Your Application Name]: Cybersecurity Challenge

## Introduction
Welcome to **django_vue_challenge**, a cybersecurity challenge designed for beginners in the field. This application provides a hands-on experience in understanding and executing basic security penetration techniques.

### Objectives
- Bypass the login page using common cybersecurity techniques.
- Perform an SQL injection to manipulate and access data.

## Getting Started

### Prerequisites
- Basic knowledge of web technologies (HTML, JavaScript, etc.).
- Familiarity with SQL and database structures.

## Setup and Installation

### Option 1: Manual Setup

#### Django Backend Setup
1. **Install Python**: Ensure you have Python installed on your system. You can download it from [python.org](https://www.python.org/downloads/).
2. **Install Django**: Run `pip install django` in your command line to install Django.
3. **Setup the Backend**: Navigate to the Django project directory and run the following commands:
   - `python manage.py makemigrations`
   - `python manage.py migrate`
   - `python manage.py runserver`

#### Vue.js Frontend Setup
1. **Install Node.js and npm**: Make sure you have Node.js and npm installed. You can download them from [nodejs.org](https://nodejs.org/).
2. **Install Vue.js**: Run `npm install vue` in your command line.
3. **Setup the Frontend**: Navigate to the Vue.js project directory and execute the following:
   - `npm install` to install dependencies.
   - `npm run serve` to start the development server.

### Option 2: Docker Setup
1. **Install Docker**: If you do not have Docker installed, download it from [docker.com](https://www.docker.com/get-started).
2. **Build and Run with Docker**: In the root directory of the project, where the Dockerfile is located, run the following commands:
   - `docker build -t django-vue-challenge .` to build the Docker image.
   - `docker run -p 8000:8000 django-vue-challenge` to run the application (assuming the backend runs on port 8000).

### Accessing the Application
- After setting up, you can access the application at `http://localhost:8000` (or the port you configured).


## Challenge Instructions

### Bypassing the Login
- Objective: Gain access to the application without a valid username or password.
- Tips:
  - Look for common vulnerabilities in login forms.
  - Think about how user input is processed and validated.

### SQL Injection
- Objective: Perform an SQL injection to retrieve or manipulate data.
- Tips:
  - Understand how the application interacts with its database.
  - Identify points where user input may be improperly sanitized.

## Learning Resources
- Link to SQL injection basics: [https://portswigger.net/web-security/sql-injection](https://portswigger.net/web-security/sql-injection)
- [Link to authentication vulnerabilities and solutions]: https://portswigger.net/web-security/authentication

## Support and Community
- Join our community [link to forum or group] for discussions and support.
- For technical issues, please open an issue on [link to issue tracker].

## Contributing
We welcome contributions from the cybersecurity community. Please read our contribution guidelines [link to guidelines] before submitting a pull request.

## License
This project is licensed under [Your License Name] - see the [LICENSE.md](LICENSE) file for details.
