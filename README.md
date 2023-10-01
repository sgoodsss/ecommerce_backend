# ecommerce_backend
Built the back end for an e-Commerce site by using a working Express.js API and configuring it to use Sequelize to interact with a MySQL database.

GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize

WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data

WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database

WHEN I open API GET routes in Postman for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Postman
THEN I am able to successfully create, update, and delete data in my database

Build out the Database Models- anytime you make a change in models, drop the database and rerun source for schema

execute associations- Make sure you set up foreign key relationships that match the column we created in the respective models.

Fill Out the API Routes to Perform RESTful CRUD Operations- Be sure to look at your module project's code for syntax help and use your model's column definitions to figure out what req.body will be for POST and PUT routes!

Seed the Database
npm run seed

Sync Sequelize to the Database on Server Start
Create the code needed in server.js to sync the Sequelize models to the MySQL database on server start.