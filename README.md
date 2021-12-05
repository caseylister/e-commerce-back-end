# E-Commerce Back-End
  
## Contents
  
* [Description](#description)
* [Installation](#installation)
* [Usage](#usage)
* [Contributions](#contributions)
* [Questions](#questions)
    
## [Description](#Contents)
  
This project creates the back-end of an e-commerce site using Express.js API, MySQL2, and Sequelize. Sequelize models are synced to the MySQL database, and API GET routes are used to fetch data for categories, products, or tags in JSON format. With POST, PUT, and DELETE routes, data is able to be successfully created, updated, and deleted.
  
## [Installation](#Contents)
  
To start, clone this repository to your local computer. From your terminal, in the root directory of the project, run npm i to download the dependencies. Initiate the database by signing into your mysql using 'mysql -u root -p' and then run 'source db/schema.sql'. Exit mysql and run 'npm run seed'. This will send the data into your db tables. From there, run 'npm start' to start your server. From there, you can use InsomniaCore to run localhost:3001 and access all api endpoints. Click the following links for walkthrough videos on how this project works!

[Schema and Seeding](https://drive.google.com/file/d/1nldurCJ78HaRUBRUSIdqIyM-dw0GUPIY/view?usp=sharing)

[GET Routes](https://drive.google.com/file/d/1GZNC_NqNes7Dn1CwAfdRazDwM_2X7udc/view?usp=sharing)

[GET Routes by ID](https://drive.google.com/file/d/1wMyJxVsI6B4hCrtJney22dM55hAWCuhD/view?usp=sharing)

[POST, PUT, DELETE Routes for Categories](https://drive.google.com/file/d/1r0B6k8o3f9XfuWJsss77rkWMkJ-iQVn9/view?usp=sharing)

[POST, PUT, DELETE Routes for Products](https://drive.google.com/file/d/1rq5ZSlMlQpjvmkm1Br8gcSNGcKWNFIEL/view?usp=sharing)

[POST, PUT, DELETE Routes for Tags](https://drive.google.com/file/d/1Wwtqmfg-6AVxrlzbZoHsiu6sYVJvgz8b/view?usp=sharing)

**ALSO, you must add a .env file to the root of this project with the following details pulled from your MySQL login information.**
DB_NAME='ecommerce_db'
DB_USER='root'
DB_PW='yourpasswordhere'
  
## [Usage](#Contents)
  
This can be used as a mock-up for an e-commerce website that wishes to use the latest technologies and keep track of their products.
     
  
## [Contributions](#Contents)
  
Thank you for your interest in assisting with my project! At this time, I will not be accepting contributions.
  
    
  
## [Questions](#Contents)
  
You can contact me by clicking the following links!
  
[Email: caseynlister@gmail.com](mailto:caseynlister@gmail.com)
  
[GitHub](https://github.com/caseylister)
  