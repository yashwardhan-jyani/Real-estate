# Real Estate

Welcome to the Real Estate project! This is a full-stack application developed using React and JavaScript. The platform allows users to post properties for sale or rent and facilitates real-time communication between clients and property owners through a chat feature.

## Features

- Property Listings: Users can post properties for selling or renting.
- Real-Time Chat: Integrated chat system for real-time communication between users and clients using sockets.
- Full-Stack Functionality: The app uses MongoDB for the database and Prisma ORM for database operations.

## Technologies Used

- Frontend: React, JavaScript
- Backend: Node.js, Express
- Database: MongoDB, Prisma ORM
- Real-Time Communication: Socket.io

## Getting Started

### Prerequisites

- Node.js and npm installed
- MongoDB instance running

### Installation

1. Clone the Repository:
    ```
    git clone https://github.com/yashwardhan-jyani/Real-estate.git
    ```

2. Navigate to the Project Directory:
    ```
    cd Real-estate
    ```

3. Install the frontend dependencies:
    ```
    cd client
    npm install
    ```

4. Install the socket dependencies:
    ```
    cd ../socket
    npm install
    ```

5. Install the backend dependencies:
    ```
    cd ../api
    npm install
    ```

6. Set up your environment variables. Create a .env file in the api directory and add the necessary configuration:
    ```
    DATABASE_URL=your_mongodb_uri
    JWT_SECRET=your_jwt_secret
    ```

7. Run the backend server:
    ```
    npm start
    ```

8. Run the frontend application:
    ```
    cd ../client
    npm run dev

    ```

## Preview


![Screenshot 2024-08-28 200413](https://github.com/user-attachments/assets/a73fd60b-a23c-4b37-b46c-82d4740c9863)
![Screenshot 2024-08-28 200454](https://github.com/user-attachments/assets/f28efb55-b2fa-44cb-9db0-9403f4dbd041)
![Screenshot 2024-08-28 200531](https://github.com/user-attachments/assets/ada08920-2b0b-4ab8-ac17-3fa1f94a0082)
