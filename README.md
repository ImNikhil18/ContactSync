# ContactSync Backend

The ContactSync Backend is a strong Node.js application that serves as the core for managing user contacts. It emphasizes secure user authentication, CRUD operations for contacts, and efficient API testing with ThunderClient. Utilizing Express.js and MongoDB, this backend offers both resilience and scalability, enhanced by JSON Web Tokens (JWT) for security.

## Features

- User Authentication: Securely register and log in users.
- Token-based Authentication: Verify users and control access using JWT.
- Add Contacts: Allow users to add their contacts.
- View and Edit Contacts: Retrieve and modify contact details.
- Delete Contacts: Remove unnecessary contacts.
- API Testing: Use ThunderClient or similar tools to test endpoints.

## Technologies Used

- Backend: Node.js, Express.js
- Database: MongoDB
- Authentication: JSON Web Tokens (JWT)
- API Testing: ThunderClient

## Setup Instructions

1. Clone the Repository:

2. Install Dependencies:
- Ensure you have Node.js and npm
- Express and nodemon and express-async-handler
- MongoDb and Mongoose
- Bcrypt for hashing password
- JSON Web Token for Authentication

4. Start the Application:

   ```
   npm run dev
   ```
   

## API Testing

Use ThunderClient or similar tools to test the endpoints. Include headers and tokens for authenticated requests.

## Contributing

Contributions are welcome! If you encounter any bugs, have feature suggestions, or want to improve the project, please open an issue or submit a pull request.


