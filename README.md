 **Task Management App** 
 A task management application built using the MERN (MongoDB, Express, React, Node) stack to help users manage tasks efficiently.

**Features**
 Add task: Quickly add new tasks with relevant details.
 Mark as Complete/Incomplete: Toggle task status to track progress.
 Mark as Important: Highlight tasks that need special attention.
 Edit Task: Modify task details as needed.
 Delete Task: Remove tasks that are no longer needed.

**Getting Started**
Follow these steps to run the project locally:

 **Prerequisites**
Ensure you have the following installed:
1.Node.js
2.npm
3.MongoDB

**Installation**
Clone the repository:
git clone https://github.com/your-username/taskManagement.git
cd taskManagement

**Install dependencies for both frontend and backend:**
# Install frontend dependencies
cd frontend
npm install

# Install backend dependencies
cd ../backend
npm install
Environment Variables Setup:

**Create a .env file in the backend folder with the following:**
env
MONGO_URI=your_mongodb_connection_string
PORT=5000

**Run the application:**
# Start backend server
cd backend
npm start

# Start frontend development server
cd ../frontend
npm start
Open http://localhost:3000 in your browser to view the app.

**Frontend**
Inside the frontend folder, you can run:
npm start: Runs the app in development mode.
npm test: Launches the test runner.
npm run build: Builds the app for production in the build folder.

**Backend**
Inside the backend folder, you can run:
npm start: Runs the server.
npm run dev: Runs the server in development mode with nodemon.

**Project Structure**
frontend/src/: Contains the React components, styles, and assets for the user interface.
backend/: Contains the Express server, MongoDB connection, and API routes.

**Learn More**
To learn more about the tools and libraries used:
React Documentation
Express Documentation
MongoDB Documentation
Node.js Documentation
