# Wanderlust

Wanderlust is a full-stack web application for managing rental property listings. Users can register, log in, create, edit, and review property listings. The app features secure authentication, session management, and a user-friendly interface.

## Features

- User authentication and registration
- Create, read, update, and delete (CRUD) rental listings
- Add and manage reviews for listings
- Flash messages for user feedback
- Secure session management
- Error handling and validation

## Tech Stack

Node.js, Express.js, MongoDB, Mongoose, EJS, ejs-mate, Passport.js, passport-local, express-session, connect-flash, dotenv, method-override

## Getting Started

1. **Clone the repository:**
2. **Install dependencies:**
3. **Set up environment variables:**
- Create a `.env` file in the root directory.
- Add the following:
  ```
  MONGODB_URI=your_mongodb_connection_string
  NODE_ENV=development
  ```

4. **Run the application:**

The server will start on `http://localhost:8080`.

## Folder Structure

- `/models` - Mongoose models
- `/routes` - Express route handlers
- `/views` - EJS templates
- `/public` - Static assets

## License

This project is for educational purposes