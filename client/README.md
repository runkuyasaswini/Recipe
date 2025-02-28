Step 1: Clone the Repository
First, clone the repository to your local machine.
git clone https://github.com/runkuyasaswini/Recipe.git
Navigate into the project folder.
cd RecipeNexus

Step 2: Set Up the Backend (Node.js / Express)
Navigate to the server directory (which contains the backend code).
cd server
Install the necessary dependencies for the backend.
npm install
Set up the environment variables:
Create a .env file in the server directory.
Add necessary environment variables like MongoDB connection string.
Run the backend server.
npm run dev
This will start the backend on port 5000 (or the port defined in .env).

Step 3: Set Up the Frontend (React.js)
Navigate to the client directory (which contains the React code).
cd ../client
Install the necessary dependencies for the frontend.bash
npm install
Run the React development server.
npm start
This will start the frontend on http://localhost:3000 (by default).

Step 4: Access the Application
Once both the frontend and backend are running, you can access the application by visiting http://localhost:3000 in your web browser.
