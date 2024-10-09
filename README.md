# CAST's-Coffee-Shop


This is a small business application that was built using Node.js, Express, and EJS. The application showcases the coffee product inventory displaying it with a card-based layout with bootstrap for the UI. It includes routes for the products, about, and contact pages and stores the data in a database. Each card displays the image of the product, and the button reveals the price when clicked on.

Table of Contents
Project Overview
Requirements
Installation
Setting up routes and linking them to menu
Separation of Concerns
Project Overview
This application will help a coffee shop owner display their menu of drinks through a visually appealing and user-friendly interface. Customers can browse through the drinks and view the details such as contents and prices by interacting with the coffee drink cards.

Requirements
Node.JS
Express
EJS
Bootstrap
Database

Installation
Step 1: Clone Github Repository
Step 2: Install dependencies, the node.js packages, and express
Step 3: Create the database and update database configuration in db.js file
Step 4: Run the application

Setting up routes and linking them to menu
Each major section of the website has its own route file stored in the pages folder in the views folder. The header menu is located in the partials folder in the pages folder. The header menu contains the nav bar that routes directly into each file. Each route is associated with an EJS file in the views folder that serves as the UI for that specific page.

Separation of Concerns
Views: The views folder contains all the UI components and is separated into EJS files.
Public: The public folder contains the database and the CSS
Database: The product.db file located in the database folder inside the public folder handles the connections and queries. It ensures data is retrieved from the database and accessed dynamically in the views folder.CAST’s Coffee Shop
This is a small business application that was built using Node.js, Express, and EJS. The application showcases the coffee product inventory displaying it with a card-based layout with bootstrap for the UI. It includes routes for the products, about, and contact pages and stores the data in a database. Each card displays the image of the product, and the button reveals the price when clicked on.

Table of Contents
Project Overview
Requirements
Installation
Setting up routes and linking them to menu
Separation of Concerns
Project Overview
This application will help a coffee shop owner display their menu of drinks through a visually appealing and user-friendly interface. Customers can browse through the drinks and view the details such as contents and prices by interacting with the coffee drink cards.

Requirements
Node.JS
Express
EJS
Bootstrap
Database

Installation
Step 1: Clone Github Repository
Step 2: Install dependencies, the node.js packages, and express
Step 3: Create the database and update database configuration in db.js file
Step 4: Run the application

Setting up routes and linking them to menu
Each major section of the website has its own route file stored in the pages folder in the views folder. The header menu is located in the partials folder in the pages folder. The header menu contains the nav bar that routes directly into each file. Each route is associated with an EJS file in the views folder that serves as the UI for that specific page.

Separation of Concerns
Views: The views folder contains all the UI components and is separated into EJS files.
Public: The public folder contains the database and the CSS
Database: The product.db file located in the database folder inside the public folder handles the connections and queries. It ensures data is retrieved from the database and accessed dynamically in the views folder.