This project is a backend application for managing contacts, built with Node.js, Express, MongoDB, and JWT for authentication.
Getting Started
Prerequisites
Node.js installed on your machine.
MongoDB instance running (local or cloud-based).
Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/MohitReezal/Contact-Manager-Backend.git
cd Contact-Manager-Backend
Install dependencies:

bash
Copy
Edit
npm install
Set up environment variables:

Create a .env file in the root directory and add the following:

env
Copy
Edit
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
Start the server:

bash
Copy
Edit
npm start
The server will run on http://localhost:5000.

API Endpoints
User Registration: POST /api/users/register
User Login: POST /api/users/login
Get All Contacts: GET /api/contacts
Create New Contact: POST /api/contacts
Update Contact: PUT /api/contacts/:id
Delete Contact: DELETE /api/contacts/:id
