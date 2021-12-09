# e-commerce-backend

![License](https://img.shields.io/static/v1?label=License&message=MIT&color=BLUE)

## Table of Contents
* [Description](#description)
* [Installation](#installation)
* [Usage](#usage)
* [Questions](#questions)

## Description
w\Write back end code for an e-commerce website. The main goal was to write models for a product, category, tag and product tag. Then to write all the CRUD method routes. After writing all the routes and models we were then tasked to link our server.js.


## Installation
Run 'npm i' in the command line to install all the necessary dependencies.
Run 'npm start' to start the server


## Usage
First you must open the MySQL terminal via "mysql -u root -p" then run "source db/schema.sql" and "SHOW DATABASES" to confirm that the database was created as "ecommerce_db". Then once the database has been created simply run "npm run seed" to populate the database.

Navigate to the insomnia app and input "http://localhost:3001/api/products/" for example, or any other routes written in the routes directory. Depending on the need you will be able to search a category by its ID, a product by its product_id and a tag by its ID. Simply change the route method to Get, Put, Post, or Delete to change the DataBase.


## Watch demo video
<img width="1279" alt="Screen Shot 2021-12-08 at 8 10 00 PM" src="https://user-images.githubusercontent.com/87675400/145333187-2910cbc7-3865-40ac-b011-647836aae96c.png">

https://watch.screencastify.com/v/aWi6hSIH9eEwXCJQp1SX


## Questions
Email me or find me on GitHub!
GitHub Username: [afunkhouser](https://www.github.com/afunkhouser)
Email: alison.m.funkhouser@gmail.com
