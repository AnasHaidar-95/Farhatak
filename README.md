# Farhatak - Wedding Planning Platform

![Farhatak Logo](Frontend/public/logo.png)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Project Structure](#project-structure)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Farhatak is a comprehensive wedding planning platform designed to connect couples with a wide range of vendors and services. From booking venues to hiring photographers, Farhatak simplifies the wedding planning process, making it an enjoyable and stress-free experience. The platform also provides an admin dashboard for managing users, vendors, and services.

## Features

- **User Authentication:** Secure user registration and login system.
- **Vendor Listings:** Browse and search for various wedding vendors.
- **Service Booking:** Book services directly from vendors.
- **Review System:** Leave and read reviews for vendors and services.
- **Admin Dashboard:** Manage users, vendors, services, and bookings.
- **User Profiles:** Manage your profile and view your bookings.
- **Vendor Profiles:** Vendors can manage their profiles and services.

## Technologies Used

### Frontend

- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [React Router](https://reactrouter.com/)
- [Axios](https://axios-http.com/)
- [Chart.js](https://www.chartjs.org/)

### Backend

- [Node.js](https://nodejs.org/)
- [Express](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [Mongoose](https://mongoosejs.com/)
- [JSON Web Token (JWT)](https://jwt.io/)
- [Bcrypt.js](https://www.npmjs.com/package/bcryptjs)
- [Multer](https://www.npmjs.com/package/multer)

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

- [Node.js](https://nodejs.org/) (which comes with npm)
- [MongoDB](https://www.mongodb.com/try/download/community)

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/Farhatak.git
   ```
2. **Navigate to the project directory:**
   ```sh
   cd Farhatak
   ```
3. **Install backend dependencies:**
   ```sh
   cd Backend
   npm install
   ```
4. **Install frontend dependencies:**
   ```sh
   cd ../Frontend
   npm install
   ```
5. **Set up environment variables:**
   - Create a `.env` file in the `Backend` directory.
   - Add the following variables:
     ```
     PORT=5000
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     ```
6. **Run the backend server:**
   ```sh
   cd ../Backend
   npm run dev
   ```
7. **Run the frontend development server:**
   ```sh
   cd ../Frontend
   npm run dev
   ```
8. Open your browser and navigate to `http://localhost:5173`

## Project Structure

The project is organized into two main directories: `Frontend` and `Backend`.

- **`Frontend/`**: Contains the React application.
  - **`src/`**: Main source code.
    - **`Admin/`**: Components for the admin dashboard.
    - **`Components/`**: Reusable components.
    - **`Pages/`**: Main pages of the application.
- **`Backend/`**: Contains the Node.js and Express server.
  - **`Controller/`**: Controllers for handling business logic.
  - **`Middleware/`**: Custom middleware for authentication and authorization.
  - **`Models/`**: Mongoose schemas for the database.
  - **`Routes/`**: API routes.

## API Endpoints

The API endpoints are defined in the `Backend/Routes/` directory. Each file corresponds to a different resource (e.g., `authRoutes.js`, `bookingRoutes.js`).

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.
