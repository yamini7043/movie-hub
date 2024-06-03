# Movie Library Web Application--movie-hub

## Features
- User authentication (Sign In/ Sign Up)
- Movie search using OMDB API
- Create and manage movie lists
- Lists can be public or private

## Tech Stack
- Frontend: React.js
- Backend: Node.js with Express.js
- Database: MongoDB
- Authentication: JWT

## Installation

1. Clone the repository:
    bash
    git clone https://github.com/your-repo/movie-library.git
    cd movie-library
    

2. Install backend dependencies:
    bash
    cd backend
    npm install
    

3. Create a .env file in the backend directory and add your MongoDB URI and JWT secret:
    env
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    

4. Start the backend server:
    bash
    npm run dev
    

5. Install frontend dependencies:
    bash
    cd ../frontend
    npm install
    

6. Start the frontend server:
    bash
    npm start
    

7. Access the application at http://localhost:3000.

## Usage
- Sign up or sign in to the application.
- Search for movies using the search bar.
- Create lists of movies, and set them as public or private.
- View your movie lists on the home page.
