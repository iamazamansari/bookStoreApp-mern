Bookstore App

📚 Introduction

The Bookstore App is a full-stack web application designed to manage a wide range of books efficiently. It allows users to browse, add, edit, and delete book details while ensuring secure user authentication and seamless data management.

🚀 Features

User Authentication (Login/Signup)

Browse and Search Books

Add, Edit, and Delete Book Records

Local Storage Integration for Persistent Data

Responsive Design for Optimal User Experience

🛠️ Tech Stack

Frontend: React.js, HTML, CSS

Backend: Node.js, Express.js

Database: MongoDB with Mongoose

State Management: Context API

Authentication: Custom Auth System

📄 Installation

Follow these steps to set up the project locally:

1. Clone the Repository
   git clone https://github.com/iamazamansari/bookstoreapp-mern.git
   cd bookStoreApp

2.Install Dependencies
npm install

3.Environment Variables Create a .env file in the root directory and add the following:
MONGO_URI=<your_mongo_connection_string>
PORT=5000

4.Run the Application
npm start

5.Access the App
Open http://localhost:5173 in your browser.

🔒 Authentication Setup

1.The AuthProvider component handles authentication logic using localStorage.

2.Ensure user details are securely stored and retrieved.

🗂️ Project Structure
/bookstoreapp
├── /backend
│ ├── index.js
│ ├── /models
│ ├── /routes
│ └── /controllers
├── /frontend
│ ├── /components
│ ├── /pages
│ ├── App.js
│ └── index.js
├── .env
├── package.json
└── README.md

🤝 Contributing

Contributions are welcome! To contribute:

1.Fork the repository.

2.Create a new branch (git checkout -b feature-branch).

3.Commit your changes (git commit -m "Add new feature").

4.Push to the branch (git push origin feature-branch).

5.Open a Pull Request.

🐞 Known Issues

Ensure that the .env file is correctly configured for MongoDB connectivity.

Fast Refresh may fail if non-component logic is mixed in component files. Keep constants/utilities in separate files.

📧 Contact

For questions or feedback, feel free to reach out to the repository owner. 😊
