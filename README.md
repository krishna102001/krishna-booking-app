<h1>KRISHNA BOOKING APP</h1>

## Overview

This repository contain the KRISHNA BOOKING APP Code build using the React.js for Frontend and Node.js for Backend.

## Features

- User can Login using a JWT
- Filter Search Functionality
- Functionality like Add hotel, Edit Hotel, Book Hotel
- Stripe Payment Integration

## Technology Used

- React.js
- Express.js
- MongoDB
- TailWindCSS

## Getting Started

1. Clone the repository and navigate to the backend directory:

   ```bash
   git clone https://github.com/krishna102001/krishna-booking-app.git
   ```

### Frontend

2. In terminal run the command:

   ```bash
   cd frontend
   npm i
   ```

3. Create a `.env` files in root directory and add the following environment variables:

   ```env
   VITE_API_BASE_URL=`http://localhost:4000`
   VITE_STRIPE_PUB_KEY="{Setup Your Public key of Stripe Payment}"
   ```

4. Start the frontend server:

   ```bash
   npm run dev
   ```

   The frontend server should now be running on `http://localhost:5173`.

### Backend

5. In terminal run the command:

   ```bash
   cd backend
   npm i
   ```

6. Create a `.env` files in root directory and add the following environment variables:

   ```env
   MONGO_CONNECTION_STRING="{Your MongoDB driver Url}"
   JWT_SECRET_KEY="{Enter The Secret Key}"
   FRONTEND_URL=`http://localhost:5173`
   CLOUDINARY_CLOUD_NAM = "{Setup Cloudinary Name}"
   CLOUDINARY_API_KEY = "{Setup Cloudinary API Key}"
   CLOUDINARY_API_SECRET = "{Setup Cloudinary API Secret}"
   STRIPE_API_KE  = "{Setup STRIPE API Key}"
   ```

7. Start the backend server:

   ```bash
   npm start
   ```

   The backend server should now be running on `http://localhost:4000`.
