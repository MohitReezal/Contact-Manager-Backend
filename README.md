# Contact Manager Backend

This project is a backend application for managing contacts, built with Node.js, Express, MongoDB, and JWT for authentication.

## Features

- **User Authentication**: Secure login and registration using JSON Web Tokens (JWT).
- **Contact Management**: Create, read, update, and delete contacts.
- **API Endpoints**: RESTful API design for seamless integration with frontend applications.

## Technologies Used

- **Node.js**: JavaScript runtime environment.
- **Express.js**: Web application framework for Node.js.
- **MongoDB**: NoSQL database for storing user and contact information.
- **Mongoose**: ODM for MongoDB to manage data schemas.
- **JWT**: For secure user authentication.

## Getting Started

### Prerequisites

- Node.js installed on your machine.
- MongoDB instance running (local or cloud-based).

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/MohitReezal/Contact-Manager-Backend.git
   cd Contact-Manager-Backend
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Set up environment variables**:

   Create a `.env` file in the root directory and add the following:

   ```env
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key
   ```

4. **Start the server**:

   ```bash
   npm start
   ```

   The server will run on `http://localhost:5000`.

## API Endpoints

- **User Registration**: `POST /api/users/register`
- **User Login**: `POST /api/users/login`
- **Get All Contacts**: `GET /api/contacts`
- **Create New Contact**: `POST /api/contacts`
- **Update Contact**: `PUT /api/contacts/:id`
- **Delete Contact**: `DELETE /api/contacts/:id`

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License.

