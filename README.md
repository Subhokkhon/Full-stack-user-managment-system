Full-Stack User Management App

A full-stack web application for managing user accounts, built with React on the frontend and Flask + Python on the backend. This app allows creating, updating, and deleting users efficiently with a simple and intuitive interface.

Features

Create Users: Add new users with email, first name, and last name.

Update Users: Edit existing user details easily.

Delete Users: Remove users from the system as needed.

Decent UI/UX Design: Clean and responsive interface built with React.

Local Database: Uses SQLite to store user data, no external databases required.

RESTful API: Flask backend provides endpoints for all CRUD operations.

Tech Stack

Frontend: React.js

Backend: Flask + Python

Database: SQLite (local database)

Communication: REST API between frontend and backend

Installation & Setup
Prerequisites

Node.js & npm

Python 3.x

Backend Setup

Navigate to the backend folder:

cd backend


Install required Python packages:

pip install -r requirements.txt


Run the Flask server:

python app.py

Frontend Setup

Navigate to the frontend folder:

cd frontend


Install dependencies:

npm install


Start the React app:

npm run dev

Project Structure
API Endpoints

GET /users - Retrieve all users

POST /users - Create a new user

PUT /users/:id - Update user details

DELETE /users/:id - Delete a user
