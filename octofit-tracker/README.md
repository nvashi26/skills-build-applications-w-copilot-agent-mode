# octofit-tracker

## Overview

The Octofit Tracker is a fitness tracking application designed to help users log their activities, manage teams, and view leaderboards. The application consists of a backend built with Django and a frontend developed using React.

## Project Structure

The project is organized into two main directories: `backend` and `frontend`.

### Backend

The backend is built using Django and includes the following components:

- **venv/**: Contains the Python virtual environment for the backend application.
- **octofit_tracker/**: The main Django application directory.
  - **\_\_init\_\_.py**: Marks the directory as a Python package.
  - **models.py**: Defines the data models for users, teams, activities, leaderboard, and workouts.
  - **serializers.py**: Contains serializers for converting complex data types into native Python data types.
  - **settings.py**: Holds the configuration settings for the Django application, including database settings and installed apps.
  - **views.py**: Defines the views for handling requests and returning responses, including API endpoints.
  - **urls.py**: Defines the URL routing for the application, mapping URLs to views.
  - **wsgi.py**: Entry point for WSGI-compatible web servers to serve the application.
  - **asgi.py**: Entry point for ASGI-compatible web servers to serve the application.
- **requirements.txt**: Lists the required Python packages for the backend application, including Django and other dependencies.

### Frontend

The frontend is developed using React and includes the following components:

- **node_modules/**: Contains the installed Node.js packages for the frontend application.
- **public/**: Holds the static files for the frontend application, such as the HTML file and images.
- **src/**: Contains the source code for the React application, including components and styles.
- **package.json**: Defines the metadata for the frontend application, including dependencies and scripts.
- **README.md**: Documentation for the frontend application.

## Setup Instructions

### Backend Setup

1. Navigate to the `backend` directory.
2. Create a Python virtual environment:
   ```
   python3 -m venv venv
   ```
3. Activate the virtual environment:
   - On Windows:
     ```
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```
     source venv/bin/activate
     ```
4. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

### Frontend Setup

1. Navigate to the `frontend` directory.
2. Install the required Node.js packages:
   ```
   npm install
   ```

## Usage

To run the backend server, navigate to the `backend` directory and use the following command:
```
python manage.py runserver
```

To run the frontend application, navigate to the `frontend` directory and use:
```
npm start
```

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.