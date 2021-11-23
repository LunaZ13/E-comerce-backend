# E commerce Backend

## Description: 
I was tasked with creating the back end for an e-commerce site. I took a working Express.js API and configured it to use Sequelize to interact with a MYSQL database. 

## Installation:
1. Clone repository: git@github.com:LunaZ13/E-comerce-backend.git
2. Run `mysql -u root -p` 
3. Enter password from .env file.
4. Run `source db/schema.sql` then `npm run seed` to seed the file.
5. Run `node server.js` to connect to server.

## Usage:
User is able to test API POST, PUT, and Delete routes, then create, update, and delete data in database. Watch demo videos below.

Intro walk through

https://user-images.githubusercontent.com/86627336/142976131-135971e2-5656-4e2c-a5ef-c1daa1938ed9.mp4

GET Routes
![GET routes](https://user-images.githubusercontent.com/86627336/142974726-3fa7f389-ec9d-40c0-882c-a606335241fd.gif)

GET Routes by ID
![GET routes by single id](https://user-images.githubusercontent.com/86627336/142974240-bc138672-fd3a-4996-b9a7-4fe42635d4b9.gif)

POST, PUT, DELETE Routes for categories
![POST, PUT, DELETE routes for categories](https://user-images.githubusercontent.com/86627336/142974620-f64af53b-e51f-45fb-a788-68f9960e4e60.gif)

## Contributing:
Feel free to fork project and reach out.

## Built With:
* MYSQL
* Node.js
* Express.js
* Sequelize
* Dotenv

## Credits:
UofM Coding Boot Camp / Refactored by Inmar Luna :grinning:

## License 
Copyright (c) [2021] [Inmar Luna]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is