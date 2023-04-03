How to deploy
This guide provides instructions on how to deploy the Mindspace application on your local machine.

Prerequisites
Before proceeding with the deployment, ensure that you have the following installed on your machine:

Git
Node.js
Deployment Steps
Open your terminal, and navigate to your desired directory.

Clone the Mindspace repository using the following command:


gh repo clone kakashi848/mindspace
Navigate to the frontend directory using the following command:


cd Mindspace-frontend
Install the required dependencies by running the following command:


npm install
Start the frontend server by running the following command:


npm start
Navigate to the backend directory using the following command:


cd mindspace-backend
Install the required dependencies by running the following command:


npm install
Start the backend server by running the following command:

npm run dev
Once both the frontend and backend servers are running, you can access the Mindspace application by visiting http://localhost:3000 in your web browser.
