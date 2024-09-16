# GDSC SNIoE Dev Team Recruitment Task
This project is a web application created for the Google Developer Student Clubs (GDSC) SNIoE Dev Team recruitment process. It allows users to submit text entries, stores them in a database, and displays recent submissions.

## Features
Simple and clean user interface
Text submission functionality
Server-side storage of submissions using SQLite
Display of recent submissions
RESTful API for submitting and retrieving entries

## Tech Stack
Frontend: HTML, CSS (with Tailwind classes)
Backend: Node.js with Express.js
Database: SQLite

## Project Structure
index.js: Main server file containing the Express.js setup, database configuration, and API routes
public/index.html: Frontend HTML file with the user interface
submissions.db: SQLite database file (created automatically when the server runs)

## Setup and Running the Project
Ensure you have Node.js installed on your system.
Clone the repository:

    git clone https://github.com/prkrsx/gdsc_website.git
    cd gdsc_website

Install the dependencies:
    
    npm install

Start the server:

    node index.js

Open a web browser and navigate to http://localhost:3000 (or the port specified in your environment).

## API Endpoints

POST /api/submissions: Submit a new entry

GET /api/submissions: Retrieve the 10 most recent submissions

## Contributing
This project is part of a recruitment task. Please refer to the GDSC SNIoE guidelines for contribution and submission details.

## Acknowledgments
Google Developer Student Clubs (GDSC) SNIoE for organizing this recruitment task
All participants in the GDSC SNIoE Dev Team recruitment process
