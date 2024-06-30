# Baatein

Baatein is a real-time chat application built using the MERN stack (MongoDB, Express.js, React.js, and Node.js) with Socket.io for real-time communication.

## Getting Started

Follow the steps below to set up and run the project locally.

### Prerequisites

Ensure you have the following installed:

- Node.js
- npm (Node Package Manager)
- MongoDB Atlas account

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/baatein.git
   cd baatein
   ```

2. Install the necessary npm packages for both the frontend and backend:

   ```bash
   cd frontend-react
   npm install
   ```

   ```bash
   cd ../backend-node
   npm install
   ```

### Environment Variables

Create a `.env` file in the `backend-node` directory with the following content:

```env
MONGO_URL=your_mongo_db_url_here
JWT_SECRET=your_jwt_secret_key_here
```

Replace `your_mongo_db_url_here` with your actual MongoDB connection string and `your_jwt_secret_key_here` with a secret key for JWT authentication.

### Running the Application

1. Start the backend server:

   ```bash
   cd backend-node
   nodemon index.js
   ```

2. Start the frontend development server:

   ```bash
   cd ../frontend-react
   npm start
   ```

### Technologies Used

- **MongoDB**: For database storage.
- **Express.js**: For building the backend API.
- **React.js**: For building the user interface.
- **Node.js**: For server-side runtime.
- **Socket.io**: For real-time communication between the client and server.

### Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

### License

This project is licensed under the MIT License.

---

### Notes

- Ensure your MongoDB Atlas cluster is running and accessible.
- Make sure to adjust any configurations specific to your development environment.

Enjoy chatting with Baatein!
