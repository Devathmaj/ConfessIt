# ConfessIt 💘

ConfessIt is a full-stack web application that allows users to share anonymous confessions and connect with others through random matchmaking. It provides a safe and anonymous space for users to express their feelings and thoughts.

## ✨ Features

*   **User Authentication:** Secure user registration and login with JWT authentication.
*   **Anonymous Confessions:** Users can post anonymous confessions and view confessions from others.
*   **Like Confessions:** Users can like confessions to show their support.
*   **Top Confessions:** View the most popular confessions based on the number of likes.
*   **Random Matchmaking:** A fun feature to randomly match with other users.
*   **User Dashboard:** A personalized dashboard for each user.
*   **Responsive Design:** A mobile-friendly and responsive user interface.

## 🛠️ Tech Stack

*   **Frontend:**
    *   React
    *   Vite
    *   Tailwind CSS
    *   Framer Motion
    *   Axios
*   **Backend:**
    *   Node.js
    *   Express
    *   MongoDB
    *   Mongoose
    *   JWT (JSON Web Tokens)
    *   bcryptjs
    *   cors

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

*   Node.js and npm installed on your machine.
*   MongoDB installed and running.

### Installation

1.  **Clone the repo**
    ```sh
    git clone https://github.com/your_username/ConfessIt.git
    ```
2.  **Install NPM packages for the frontend**
    ```sh
    cd ConfessIt
    npm install
    ```
3.  **Install NPM packages for the backend**
    ```sh
    cd backend
    npm install
    ```
4.  **Create a `.env` file in the `backend` directory and add the following variables:**
    ```
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    ```
5.  **Start the backend server**
    ```sh
    npm start
    ```
6.  **Start the frontend development server**
    ```sh
    cd ..
    npm run dev
    ```

## API Endpoints

The following are the available API endpoints:

| Method | Endpoint               | Description                               |
| ------ | ---------------------- | ----------------------------------------- |
| `POST` | `/register`            | Register a new user.                      |
| `POST` | `/login`               | Login an existing user.                   |
| `GET`  | `/dashboard`           | Get dashboard data (protected).           |
| `GET`  | `/userpanel`           | Get user panel data (protected).          |
| `POST` | `/confessions`         | Create a new confession (protected).      |
| `GET`  | `/confessions`         | Get all confessions.                      |
| `POST` | `/confessions/:id/like`| Like a confession.                        |
| `GET`  | `/confessions/top`     | Get the top 5 most liked confessions.     |

## 📸 Screenshots

*(Add your screenshots here)*

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.