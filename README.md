# Project Description

This project is a user registration and login system built using Node.js, Express.js, and MongoDB. It provides a simple web interface for users to sign up with their name and password, and then log in to their account. The project utilizes the MVC (Model-View-Controller) architectural pattern to structure the codebase.

**Features**
- User registration: Users can create an account by providing their name and password.
- User login: Registered users can log in to their account using their credentials.
- Home page: Upon successful login, users are greeted with a personalized home page that displays a welcome message and congratulations.

**Technologies Used**
- Node.js: A JavaScript runtime environment for server-side development.
- Express.js: A web application framework for Node.js that simplifies the development of web applications.
- MongoDB: A NoSQL database used to store user information.
- Mongoose: An Object Data Modeling (ODM) library for MongoDB and Node.js, providing a higher-level abstraction for working with MongoDB.
- HTML/CSS: Used for creating the user interface and styling the web pages.
- Handlebars (hbs): A templating engine for Express.js used to dynamically generate HTML content.

**Installation and Setup**
1. Clone the repository from GitHub.
2. Install Node.js and MongoDB if not already installed on your system.
3. Navigate to the project directory and run `npm install` to install the project dependencies.
4. Start the MongoDB server.
5. Run the command `node src/index.js` to start the application.
6. Open a web browser and visit `http://localhost:3000` to access the application.

Feel free to explore and enhance the project by adding new features or improving the existing ones.

**Note:** Make sure to configure the MongoDB connection settings in `mongodb.js` file to match your local MongoDB setup.
