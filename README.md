# GraphQL Product Manager

This repository contains a project focused on building a GraphQL API and integrating it with client applications, in our case, managing a library of products The project includes setting up a GraphQL server, create schemas, queries, and mutations, and implement advanced queries and mutations. We manage product information (CRUD operations) via GraphQL queries and mutations, retrieve all products or a specific product by ID and use MongoDB for product data storage and SQLite for category data.

## Setup Instructions

Follow these steps to set up the project locally on your machine:

1. **Clone the Repository:**

Run the following command to clone the repository: 
git clone https://github.com/dani-yash/graphql-product-manager.git
cd graphql-project

2. **Install Dependencies:**

Ensure you have Node.js and npm installed on your machine. Then, run the following command to install the project dependencies: npm install

3. **Start the Server:**
To start the GraphQL server, run: npm start

4. **Open GraphQL Playground:**
Once the server is running, open your browser and navigate to http://localhost:8080 to access the GraphQL Playground where you can interact with the API.

## Technologies Used

	•	Node.js: A JavaScript runtime built on Chrome’s V8 JavaScript engine.
	•	Express: A minimal and flexible Node.js web application framework.
	•	GraphQL: A query language for APIs and a runtime for executing those queries.
	•	MongoDB: A NoSQL database for storing and retrieving data.
	•	Mongoose: An ODM (Object Data Modeling) library for MongoDB and Node.js.
	•	SQLite: A relational database management system embedded within the project for managing categories.
	•	Sequelize: An ORM (Object Relational Mapper) for Node.js, used for managing SQLite.
	•	Lodash: A JavaScript utility library delivering consistency, modularity, and performance.
	•	Casual: A fake data generator for populating the database.
	•	Studio 3T: A GUI and IDE for MongoDB.

