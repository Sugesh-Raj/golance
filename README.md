# GoLance

GoLance is a comprehensive freelance and task-bidding web platform. It connects users who need tasks completed with freelancers who bid on and execute those tasks.

## 🚀 Features

* **User Authentication & Profiles:** Secure registration and login system with customizable user profiles.
* **Task Management:** Users can post new tasks, browse available tasks, and manage their assigned or posted jobs.
* **Bidding System:** Freelancers can place bids on open tasks, while task owners can review bids and select the best candidate.
* **Wallet & Credits:** An integrated virtual wallet system for managing user credits, balances, and transactions.
* **Real-Time Messaging:** Built-in live chat feature utilizing WebSockets for seamless communication between task posters and assigned freelancers.

## 🛠️ Technology Stack

**Frontend:**
* React.js
* Vite for fast bundling and development
* Real-time WebSocket integration for messaging

**Backend:**
* Java / Spring Boot
* Spring Security (JWT-based authentication)
* WebSockets for real-time chat functionality
* RESTful API architecture

## 📁 Project Structure

* **`/frontend`**: Contains the React frontend web application.
* **`/backend`**: Contains the Spring Boot server handling business logic, database interactions, and API endpoints.

## 🏃 Getting Started

### Frontend
To run the frontend application locally:
1. Open a terminal and navigate to the `frontend` directory:
   ```bash
   cd frontend
   ```
2. Install the required dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```

### Backend
To run the backend application locally:
1. Open a terminal and navigate to the `backend` directory:
   ```bash
   cd backend
   ```
2. Run your Spring Boot application using your IDE or via the command line (using Maven or Gradle). Make sure your database configurations in `application.properties` are set correctly before starting.
