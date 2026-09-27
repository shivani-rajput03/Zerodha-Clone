Zerodha Clone

<p align="center">
  <strong>A full-stack stock trading platform inspired by the Zerodha user experience.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React.js-Frontend-61DAFB?logo=react&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-Backend-339933?logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Express.js-API-000000?logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-Database-47A248?logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-GitHub-F05032?logo=git&logoColor=white" />
</p>

📌 Overview

Zerodha Clone is a full-stack web application developed as an educational project to understand how a modern online stock-trading platform can be structured.

The project is divided into three main applications:

Frontend — Public landing pages, product information, pricing, support and account creation.

Dashboard — Trading-oriented interface containing watchlist, holdings, orders, positions and funds.

Backend — REST APIs, authentication, database connectivity and portfolio-related data management.

Disclaimer: This is an educational project and is not affiliated with, endorsed by, or connected to Zerodha.

✨ Key Features

🌐 Frontend

Landing page

Navigation and footer

Products section

Pricing and brokerage information

About section

Support section

User signup

Responsive React-based interface

📊 Trading Dashboard

Dashboard overview

Stock watchlist

Stock search

Buy action interface

Holdings

Orders

Positions

Funds

Apps section

Portfolio summary and visualizations

🔐 Backend

User registration and authentication

JWT-based authentication

Password hashing with bcryptjs

MongoDB integration using Mongoose

REST API routes

Holdings management

Orders management

Positions management

🖥️ Screenshots

Landing Page

<p align="center">
  <img src="screenshots/landing-page.png" width="90%" alt="Zerodha Clone Landing Page">
</p>

Trading Dashboard

<p align="center">
  <img src="screenshots/dashboard-holdings.png" width="90%" alt="Zerodha Clone Dashboard">
</p>

🛠️ Tech Stack

Layer

Technologies

Frontend

React.js, JavaScript, HTML, CSS

Dashboard

React.js, JavaScript, CSS

Backend

Node.js, Express.js

Database

MongoDB, Mongoose

Authentication

JWT, bcryptjs

Version Control

Git, GitHub

Development

Visual Studio Code, npm

🏗️ Project Architecture

                         ┌──────────────────────┐
                         │       Frontend       │
                         │   React.js / UI      │
                         └──────────┬───────────┘
                                    │
                                    │ API Requests
                                    ▼
                         ┌──────────────────────┐
                         │       Backend        │
                         │ Node.js + Express.js │
                         └──────────┬───────────┘
                                    │
                                    │ Mongoose
                                    ▼
                         ┌──────────────────────┐
                         │       MongoDB        │
                         │       Database       │
                         └──────────────────────┘

                         ┌──────────────────────┐
                         │      Dashboard       │
                         │ React.js Trading UI  │
                         └──────────┬───────────┘
                                    │
                                    └──── API Requests ────► Backend

📂 Project Structure

Zerodha-Clone/
│
├── backend/
│   ├── Controllers/
│   ├── Routes/
│   ├── model/
│   ├── schemas/
│   ├── SecretToken.js
│   ├── index.js
│   └── package.json
│
├── dashboard/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   └── data/
│   └── package.json
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   └── landing_page/
│   └── package.json
│
├── screenshots/
│   ├── landing-page.png
│   └── dashboard-holdings.png
│
├── .gitignore
└── README.md

⚙️ Getting Started

Prerequisites

Make sure the following are installed:

Node.js

npm

MongoDB / MongoDB Atlas

Git

1. Clone the Repository

git clone https://github.com/shivani-rajput03/Zerodha-Clone.git
cd Zerodha-Clone

2. Backend Setup

cd backend
npm install

Create a .env file inside the backend directory:

MONGO_URL=your_mongodb_connection_string
TOKEN_KEY=your_secret_key

Start the backend:

node index.js

3. Frontend Setup

Open a new terminal:

cd frontend
npm install
npm start

4. Dashboard Setup

Open another terminal:

cd dashboard
npm install
npm start

🔐 Environment Variables & Security

The backend uses environment variables for sensitive configuration.

Example:

MONGO_URL=your_mongodb_connection_string
TOKEN_KEY=your_secret_key

Never commit sensitive information such as:

.env

Also keep the following private:

MongoDB credentials

JWT/token secrets

API keys

Other application credentials

📚 Learning Outcomes

This project provided practical experience with:

React component development

Reusable UI components

REST API development

Frontend-backend integration

MongoDB and Mongoose

User authentication

JWT authentication

Password hashing

Application state management

Git and GitHub

Full-stack project organization

🚀 Future Improvements

Real-time market data

Complete buy/sell transaction workflow

Portfolio analytics

Advanced stock charts

Notifications

Improved validation and security

Enhanced responsive design

👩‍💻 Author

Shivani Rajput

Computer Science & Engineering Student

<p>
  <a href="https://github.com/shivani-rajput03">GitHub</a> •
  <a href="https://www.linkedin.com/in/shivani-rajput-042046342">LinkedIn</a>
</p>

⚠️ Disclaimer

This project is created strictly for educational and learning purposes.

It is inspired by the interface and workflow of an online stock-trading platform and is not affiliated with, endorsed by, or connected to Zerodha.

It should not be used for real financial transactions.

<p align="center">
  ⭐ If you found this project useful, feel free to explore the repository.
</p>