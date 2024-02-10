#Bit-to-Bit
This project is a simple demonstration of WebSocket communication between a React frontend and a Spring Boot backend.

Prerequisites
Before running this project, make sure you have the following installed:

Node.js and npm (for React frontend)
Java JDK (for Spring Boot backend)
Maven (optional, but recommended for managing dependencies in the backend)
Getting Started
Follow the steps below to get this project up and running on your local machine:

Backend (Spring Boot)
Clone this repository.
Navigate to the backend directory.
Open the project in your preferred IDE.
Build the project using Maven: mvn clean install
Run the Spring Boot application: mvn spring-boot:run
The backend server should now be running on http://localhost:8080.
Frontend (React)
Navigate to the frontend directory.
Install dependencies using npm: npm install
Start the React development server: npm start
The frontend should now be running on http://localhost:3000.
Usage
Once both the backend and frontend servers are running, you can interact with the WebSocket by opening the frontend in your browser.

Open your browser and navigate to http://localhost:3000.
You should see a simple UI with WebSocket connection status.
Interact with the UI to send and receive WebSocket messages.
Folder Structure
backend: Contains the Spring Boot backend code.
frontend: Contains the React frontend code.
Contributing
Contributions are welcome! If you find any issues or have suggestions for improvement, feel free to submit a pull request.

License
This project is licensed under the MIT License.
