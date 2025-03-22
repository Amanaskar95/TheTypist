# Typing Website (MERN Stack)

## Overview
A web-based typing practice application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. This platform helps users improve their typing speed and accuracy by providing real-time feedback and tracking progress over time.

## Features
- **User Authentication** (Login/Register using JWT)
- **Typing Tests** with various difficulty levels
- **Real-time WPM (Words Per Minute) and Accuracy Calculation**
- **Leaderboards** to compare scores with other users
- **Progress Tracking** with historical typing data
- **Responsive UI** built with React
- **Backend API** for managing users and scores

## Tech Stack
- **Frontend:** React.js, Redux, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB, Mongoose
- **Authentication:** JSON Web Tokens (JWT), bcrypt.js
- **Deployment:** Vercel (Frontend), Render/Heroku (Backend)

## Installation
### Prerequisites
- Node.js (>= 14.x)
- MongoDB (Local or Atlas)

### Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/typing-website.git
   cd typing-website
   ```
2. Install dependencies for frontend and backend:
   ```sh
   cd client
   npm install
   cd ../server
   npm install
   ```
3. Create a `.env` file in the `server` directory and configure the following:
   ```env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```
4. Run the backend server:
   ```sh
   cd server
   npm start
   ```
5. Run the frontend:
   ```sh
   cd client
   npm start
   ```
6. Open `http://localhost:3000` in your browser.

## API Endpoints
### Authentication
- `POST /api/auth/register` - Register a new user
- `POST /api/auth/login` - Login user and get token

### Typing Test
- `GET /api/test` - Fetch typing test data
- `POST /api/test/submit` - Submit typing results

### Leaderboard
- `GET /api/leaderboard` - Get top scores

## Contribution
Contributions are welcome! Feel free to submit issues or pull requests.

## License
This project is licensed under the MIT License.

## Contact
For any queries, contact **Aman Kumar** at [amanaskar8877@gmail.com](mailto:amanaskar8877@gmail.com).

