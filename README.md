# Ghana Tourism Aid Backend

## Overview

The Ghana Tourism Aid Backend is the server-side application for a tourism assistance platform designed to help tourists discover popular tourist attractions, cultural heritage sites, hotels, restaurants, and other points of interest across Ghana.

This backend provides APIs for managing tourist destinations, user accounts, reviews, favorites, and location-based recommendations.

---

## Objectives

- Help tourists discover attractions in Ghana.
- Provide accurate information about tourist destinations.
- Allow users to create accounts and save favorite places.
- Enable users to rate and review destinations.
- Support location-based search.

---

## Features

- User Registration and Login
- Tourist Attraction Management
- Search Tourist Sites
- Hotel and Restaurant Listings
- Reviews and Ratings
- Favorite Destinations
- Location-based Recommendations
- Secure Authentication
- RESTful API

---

## Technology Stack

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- dotenv
- Git & GitHub

---

## Project Structure

```
backend/
│
├── controllers/
├── models/
├── routes/
├── middleware/
├── config/
├── utils/
├── uploads/
├── .env
├── package.json
├── server.js
└── README.md
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/lukeman1222/backend.git
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

or

```bash
npm start
```

---

## Environment Variables

Create a `.env` file and include:

```
PORT=5000
MONGODB_URI=your_database_url
JWT_SECRET=your_secret_key
```

---

## API Endpoints

### Authentication

- POST /api/auth/register
- POST /api/auth/login

### Tourist Attractions

- GET /api/attractions
- GET /api/attractions/:id
- POST /api/attractions
- PUT /api/attractions/:id
- DELETE /api/attractions/:id

### Reviews

- POST /api/reviews
- GET /api/reviews/:attractionId

### Favorites

- GET /api/favorites
- POST /api/favorites

---

## Future Improvements

- AI-powered travel recommendations
- Interactive maps
- Tour guide booking
- Weather updates
- Event recommendations
- Multiple language support

---

## Contributors

- Abubakar Lukeman Agambilla
- Group Members

---

## License

This project is for academic purposes.

