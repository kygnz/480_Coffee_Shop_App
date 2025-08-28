## Coffee Shop Application

This project was created for CS 480 at UIC with Rasleen Dhaliwal, Fariha Siyadath, and Kyla Gonzalez.

Our app uses html, css, javascript and postgresql to create a user interface for our coffee shop database relational schema

Our app opens to a login page. Here are 3 login options, pre-initialized for demonstration: Manager: Username "rasleen", password "a"
Barista: Username "fariha", password "b"
Hybrid (barista and manager): Username "kyla", password "c"


## To run:
- In the terminal, cd to main folder 480_Coffee_Shop_App
- install dependencies: npm install
- create the database: createdb -U postgres coffeedb
- load schema: psql -U postgres -d coffeedb -f schema.sql
- start express.js: node server.js
