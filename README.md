# Social Media App

**Social Media App** is a personal side project developed with a passion for coding and a vision to create a platform for users to connect, share, and engage in a social networking experience. This project combines a robust backend and a user-friendly frontend to provide a seamless experience for users.

## Features

- **User Authentication**: Secure user registration and login using JSON Web Tokens (JWT) and bcrypt for password hashing.
- **Dark Mode and Light Mode**: Enhance your user experience with the ability to toggle between dark and light modes.

- **Responsive Design**: The app is designed to be accessible on various devices and screen sizes.

- **State Management**: Utilizes Redux and Redux Toolkit for efficient state management.

- **Routing**: Uses React Router for client-side routing, providing a smooth and responsive user interface.

- **Database Integration**: MongoDB with Mongoose is employed for data storage and management.

## Backend

The backend of the Social Media App is powered by Node.js and Express. It provides a RESTful API for handling user authentication, post creation, and file uploads. MongoDB, a NoSQL database, is used for data storage.

### Environment Variables (.env)

To run the backend, create a `.env` file in the backend directory and set the following environment variables:

```dotenv
PORT=3001
MONGO_URL=<Your MongoDB URI>
JWT_SECRET=<Your JWT Secret>
