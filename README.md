# App Backend

A Node.js/Express backend server providing authentication APIs for the RN App.

## Features

- User authentication (login/register)
- JWT token-based authentication
- MongoDB database integration
- Input validation
- Password hashing with bcrypt

## Prerequisites

- Node.js
- MongoDB
- npm

## Installation

1. Clone the repository
2. Install dependencies:
```sh
npm install express
npm install nodemon
npm install mongoose
npm install cors
npm install bcrypt
npm install jsonwebtoken
```
3. Create a `.env` file in the root directory and add the following environment variables:
```sh
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=3000
HOST=your_host_ip
```

## Usage
- Start the server:
```sh
npm start
```
- The server will run on `http://localhost:3000`

## API Endpoints

### Auth Routes


- POST `/api/auth/register`
- POST `/api/auth/login`

![Cuplikan layar 2025-01-12 215128](https://github.com/user-attachments/assets/b2581b90-0a68-4871-af58-84fce2f0a0ef)
![Cuplikan layar 2025-01-12 215106](https://github.com/user-attachments/assets/44773923-ed3a-4a2f-9f3f-c09ea02fa775)
![Cuplikan layar 2025-01-12 215154](https://github.com/user-attachments/assets/e01a4eee-0362-440f-8831-74029c5ff19f)
![Cuplikan layar 2025-01-12 215217](https://github.com/user-attachments/assets/35dad6e6-dda8-41cb-9528-158be8c4b5b2)
![Cuplikan layar 2025-01-12 215226](https://github.com/user-attachments/assets/bf584ff0-fec6-436d-8bcf-6aed5f8fcc65)

