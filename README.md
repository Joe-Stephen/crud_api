Node.js Express CRUD API

Overview
This project implements a simple CRUD (Create, Read, Update, Delete) API using Node.js and Express. It provides RESTful endpoints for managing user resources, storing data in memory, and connecting to MongoDB.

📋 Table of Contents

Installation
Usage
Endpoints
Environment Variables
Contributing
License

🚀 Installation

Clone the repository:
git clone https://github.com/your-username/your-repo.git

Install dependencies:
npm install

▶️ Usage
Run the server using:
npm start
The server will run on http://localhost:5000 by default.

🛣️ Endpoints
GET /users: Get a list of all users.
GET /users/:id: Get details of a specific user by ID.
POST /users: Create a new user.
DELETE /users/:id: Delete a specific user by ID.
PATCH /users/:id: Edit the details of a specific user by ID.

⚙️ Environment Variables
PORT: Port for the server to run on. The default is 5000.
MONGO_URI: MongoDB connection string.
(I am not connecting this API to MongoDB in this project, even though I wanted to show how you could do the same.)
Ensure to set up the dotenv file with these variables.

🤝 Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

📄 License
This project is licensed under the ISC License.
