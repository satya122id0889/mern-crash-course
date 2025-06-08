Here's the complete `README.md` with the installation section filled in:

```markdown
# MERN Crash Course

🚀 A full-stack MERN (MongoDB, Express, React, Node.js) project to build a simple e-commerce application from scratch.

[![YouTube Video](https://img.shields.io/badge/YouTube-Watch-red?style=for-the-badge&logo=youtube)](https://youtu.be/O3BUHwfHf84)

---

## Features

- User authentication with JWT
- Product listing and details
- Add to cart functionality
- Admin panel for product management
- RESTful API backend
- Responsive React frontend

---

## Technologies Used

- **Frontend:** React, Redux, Axios, React Router
- **Backend:** Node.js, Express.js
- **Database:** MongoDB, Mongoose
- **Authentication:** JWT, bcryptjs
- **Others:** dotenv, concurrently, nodemon

---

## Getting Started

### Prerequisites

- Node.js (v14+) and npm installed
- MongoDB installed and running locally or MongoDB Atlas account

### Installation

1. Clone the repo
```bash
git clone https://github.com/your-username/mern-crash-course.git
cd mern-crash-course
```

2. Install dependencies for both frontend and backend
```bash
# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install
```

3. Set up environment variables
```bash
# In backend directory, create a .env file with:
touch .env
```

Add these variables to your `.env` file:
```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
PORT=5000
```

4. Run the application
```bash
# From project root directory, run both frontend and backend:
npm run dev
```

This uses `concurrently` to run both servers simultaneously.

---

## Project Structure

```
mern-crash-course/
├── backend/            # Express.js server
│   ├── config/        # DB configuration
│   ├── controllers/   # Route controllers
│   ├── models/        # Mongoose models
│   ├── routes/        # API routes
│   ├── middleware/    # Custom middleware
│   └── server.js      # Server entry point
│
├── frontend/          # React application
│   ├── public/        # Static files
│   ├── src/
│   │   ├── components # React components
│   │   ├── redux/     # Redux store and slices
│   │   ├── screens/   # Page components
│   │   └── App.js     # Main component
│   └── ...            
│
├── .gitignore
└── package.json       # Root package.json
```

---

## Available Scripts

In the project directory, you can run:

- `npm run dev` - Runs both frontend and backend in development mode
- `npm run server` - Runs only the backend server
- `npm run client` - Runs only the frontend
- `npm run build` - Builds the frontend for production

---

## Related Video Tutorial

This project is based on the YouTube tutorial:  
[MERN Stack E-Commerce Crash Course](https://youtu.be/O3BUHwfHf84)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

### Additional Notes:
1. Make sure to replace `your-username` with your actual GitHub username
2. Update the YouTube link if needed
3. Add a LICENSE file if you haven't already
4. You might want to add screenshots of your application
5. Consider adding a "Demo" section with a live link if deployed

Would you like me to add any additional sections or make any modifications to this README?
