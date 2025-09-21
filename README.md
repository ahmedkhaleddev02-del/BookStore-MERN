# BookStore-MERN

## Project Description
BookStore-MERN is a full-stack web application built using the MERN stack (MongoDB, Express, React, Node.js). It allows users to browse books, add new books, update existing ones, and delete them. The project can be extended in the future to include user authentication, reviews, and advanced search features.

---

## Tech Stack

- **Frontend:** React.js  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Package Manager:** npm  
- **Architecture:** Clear separation of concerns with folders for models, routes, config, and frontend.

---

## Project Structure

```text
BookStore-MERN/
├── config/           # Project configuration (e.g., database connection)
├── models/           # MongoDB models
├── routes/           # API routes
├── frontend/         # React frontend
│   ├── src/
│   ├── public/
│   └── ...
├── server.js         # Entry point for backend
├── package.json
└── .gitignore

## Installation & Setup

Clone the repository to your local machine:

```bash
git clone https://github.com/ahmedkhaleddev02-del/BookStore-MERN.git
cd BookStore-MERN

npm install

cd frontend
npm install
npm run dev

Create a .env file in the project root with the following variables:
MONGO_URI=your_mongodb_connection_string
PORT=5000
JWT_SECRET=your_jwt_secret


Make sure your .gitignore includes the following:
node_modules/
.env
.history/
dist/
build/



