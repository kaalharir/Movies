# Full Stack Movie Review Application

This project is a full-stack movie review application developed as part of a comprehensive video course on the freeCodeCamp.org YouTube channel. The application utilizes MongoDB, Java, Spring Boot, and React to provide a seamless and feature-rich experience for users.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Backend Details](#backend-details)
- [Frontend Details](#frontend-details)
- [Contributing](#contributing)
- [License](#license)

## Overview

The Full Stack Movie Review Application is designed to allow users to explore and review movies. It provides a user-friendly interface for browsing movies, reading reviews, and adding their own reviews. The project follows best practices in full-stack development, ensuring a clean separation of concerns between the backend and frontend.

## Features

- **Backend:**
  - User Authentication
  - Movie and Review CRUD Operations
  - MongoDB Atlas Integration
  - RESTful API Endpoints
  - Integration Testing

- **Frontend:**
  - Responsive User Interface
  - Movie Listing and Details
  - User Reviews Section
  - Material-UI Components
  - React Routing for Seamless Navigation
  - Integration with Backend API

## Getting Started

To run the project locally, follow these steps:

### Backend Setup
1. Clone the repository: `git clone https://github.com/kaalharir/Movies.git`
2. Navigate to the backend directory: `cd backend`
3. Install dependencies: `npm install`
4. Configure MongoDB Atlas credentials in `.env` file.
5. Run the server: `npm start`

### Frontend Setup
1. Navigate to the frontend directory: `cd frontend`
2. Install dependencies: `npm install`
3. Run the development server: `npm start`

Visit `http://localhost:3000` in your web browser to access the application.

## Project Structure

The project is structured into separate `backend` and `frontend` directories. Each directory contains its own README.md file with detailed instructions for setting up and running the respective components.

## Backend Details

The backend is developed using Java and Spring Boot. It provides RESTful API endpoints for handling user authentication, movie data, and user reviews. MongoDB Atlas is used as the database, ensuring a scalable and efficient backend architecture.

### Backend Directory Structure
- `/src`: Contains the source code for the Spring Boot application.
- `/test`: Integration tests for backend functionality.

## Frontend Details

The frontend is developed using React and integrates with the backend API to fetch and display movie data. Material-UI components are used for building a responsive and visually appealing user interface.

### Frontend Directory Structure
- `/src`: Contains the source code for the React application.
- `/public`: Static assets and HTML template.

## Contributing

Contributions are welcome! If you'd like to contribute to the project, please follow our [contribution guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).
