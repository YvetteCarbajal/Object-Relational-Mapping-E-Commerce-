## Acceptance Criteria 
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database

## Built With 

MySQL12 https://www.npmjs.com/package/mysql2
Sequelize https://www.npmjs.com/package/sequelize
dotenv https://www.npmjs.com/package/dotenv

## SOURCE CODE
https://git.bootcampcontent.com/University-of-Texas-at-Austin/UTA-VIRT-FSF-PT-09-2023-U-LOLC/-/blob/main/13-ORM/01-Activities/28-Stu_Mini-Project/Main/models/Location.js?ref_type=heads
https://git.bootcampcontent.com/University-of-Texas-at-Austin/UTA-VIRT-FSF-PT-09-2023-U-LOLC/-/blob/main/13-ORM/01-Activities/28-Stu_Mini-Project/Main/models/index.js?ref_type=heads
https://git.bootcampcontent.com/University-of-Texas-at-Austin/UTA-VIRT-FSF-PT-09-2023-U-LOLC/-/blob/main/13-ORM/01-Activities/28-Stu_Mini-Project/Main/models/Traveller.js?ref_type=heads
https://git.bootcampcontent.com/University-of-Texas-at-Austin/UTA-VIRT-FSF-PT-09-2023-U-LOLC/-/blob/main/13-ORM/01-Activities/28-Stu_Mini-Project/Main/routes/api/locationRoutes.js?ref_type=heads
https://stackoverflow.com/questions/64842029/put-and-get-methods-with-router-put-and-router-delete-not-working-express
https://stackoverflow.com/questions/69109127/sequelize-and-mysql-associations

