# Fruits-N-Vegetables-MongoDB
Fruits and Vegetables Web App
This is a web application built with Express.js to serve routes for managing fruits and vegetables.

Features
CRUD operations for fruits and vegetables
View fruits and vegetables lists
User-friendly interface
Separate routes for fruits and vegetables
Technologies Used
Express.js: for handling server-side logic and routing
Mongoose: for MongoDB object modeling
dotenv: for loading environment variables from a .env file
jsx-view-engine: for rendering JSX views
method-override: for supporting PUT and DELETE HTTP methods
MongoDB: as the database
Setup
Clone the repository:

bash
Copy code
git clone <repository_url>
Install dependencies:

Copy code
npm install
Create a .env file in the root directory and define environment variables:

makefile
Copy code
PORT=5050
MONGODB_URI=<your_mongodb_uri>
Start the server:

sql
Copy code
npm start
Access the application in your browser at http://localhost:5050

Routes
Fruits: /fruits
GET / - View all fruits
POST / - Add a new fruit
GET /:id - View details of a specific fruit
PUT /:id - Update details of a specific fruit
DELETE /:id - Delete a specific fruit
Vegetables: /vegetables
GET / - View all vegetables
POST / - Add a new vegetable
GET /:id - View details of a specific vegetable
PUT /:id - Update details of a specific vegetable
DELETE /:id - Delete a specific vegetable