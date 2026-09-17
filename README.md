# python-flask-login
A simple Flask-based web application demonstrating user login, session-based authentication, protected routes, and logout functionality.

````markdown
# Flask Login Authentication System

A simple web-based login authentication system built with **Python and Flask**. The application demonstrates user login, session management, protected routes, and logout functionality.

## Features

- User login with username and password
- Session-based authentication
- Protected welcome page
- Logout functionality
- Automatic redirection for unauthenticated users
- Simple HTML login interface
- Flask debug mode for development

## Technologies Used

- Python
- Flask
- HTML
- Git & GitHub

## Project Structure

```text
Python_Flask/
│
├── app.py
├── README.md
├── .gitignore
└── venv/
````

> `venv/` is excluded from GitHub using `.gitignore`.

## Login Credentials

For demonstration purposes:

```text
Username: admin
Password: 123
```

## How to Run

### 1. Clone the repository

```bash
git clone YOUR_REPOSITORY_URL
cd Python_Flask
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the virtual environment

**Windows PowerShell:**

```powershell
.\venv\Scripts\Activate.ps1
```

### 4. Install Flask

```bash
python -m pip install flask
```

### 5. Run the application

```bash
python -m flask --app app run --debug
```

### 6. Open in browser

Visit:

```text
http://127.0.0.1:5000
```

## Application Flow

```text
Login Page
    ↓
Valid Credentials
    ↓
Session Created
    ↓
Welcome Page
    ↓
Logout
    ↓
Login Page
```

If invalid credentials are entered, the application displays an error message.

## Learning Objectives

This project was created to practice:

* Flask application structure
* Flask routing
* GET and POST requests
* HTML forms
* Request data handling
* Sessions
* URL routing with `url_for()`
* Redirects
* Basic authentication concepts
* Git and GitHub workflow

## Future Improvements

* Password hashing
* Database integration
* User registration
* Better error messages
* Improved UI/UX
* Environment variables for secret keys
* Persistent user authentication

## Author

**Sandip Paul**

GitHub: `YOUR_GITHUB_USERNAME`

````

### 2. Add it to Git

Since you already initialized Git, run:

```powershell
git add README.md
````

Then:

```powershell
git commit -m "Add professional README"
```

And push:

```powershell
git push
```

### 3. Your GitHub repository will now look like

```text
flask-login-app
│
├── app.py
├── README.md
└── .gitignore
```

GitHub will automatically display `README.md` on the main repository page.

**One thing to change:** Replace:

```text
YOUR_REPOSITORY_URL
```

and

```text
YOUR_GITHUB_USERNAME
```

with your actual GitHub details.
