# Simple-OnCall-Roster-Template-WebApp
On-Call Roster Template
This project is a simple On-Call Roster Management web application built using Flask and MongoDB, allowing teams to manage their on-call schedules. Users can easily add, edit, or delete team members, specifying their roles, teams, and availability dates.

Features
Team Segmentation: Teams are organized into categories like SRE Payments, SRE UPI, SRE Platform, NetOps, and Core Infra.
Add/Edit User: A user-friendly form for adding or editing users, including fields like name, email, team, role, and availability dates.
Manage Users: Admins can easily edit or delete users from the roster.
Responsive UI: A clean and simple interface built with HTML and CSS, with a focus on usability.

Tech Stack
Backend: Flask (Python)
Database: MongoDB (via pymongo)
Frontend: HTML/CSS (using Flask's template rendering)
Environment Management: .env for database connection
Deployment: Can be easily deployed to Heroku (Procfile included)

Installation
Clone the repository:
`git clone <your-repo-url>`
`cd on-call-roster`

Install dependencies:
`pip install -r requirements.txt`

Set up your MongoDB connection string in the .env file:
`MONGODBURL=mongodb://<username>:<password>@localhost:27017/{Your_Collection}`
Run the application:
`python app.py`
Access the app by visiting `http://localhost:5000` in your browser.
