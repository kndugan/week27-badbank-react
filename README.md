# Week 27 BadBank with React

## Description

In this project, I've created a MERN Banking Application. Users can create accounts, make deposits, withdrawls, and check balances.

The starter code was provided by MIT xPro.

## Installation Guidelines

In the project directory,

#### 1. Install Dependencies

To install all of the app dependencies, including Node JS, MongoDB, Express, CORS, and LowDB, run:

### `npm install`

#### 2. Begin Running Docker

In terminal, run the following command:

### `docker run -p 27017:27017 --name badbank -d mongo`

Once Docker is running, check that it's working, open [http://localhost:27017](http://localhost:27017) to view in your browser. 

#### 3. Run the application 

In terminal, run the following command to launch the server and application: 

### `node index.js`

Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.

## Technology Used

[MongoDB](https://www.mongodb.com/)
[Express](http://expressjs.com/)
[React](https://github.com/facebook/create-react-app)
[NodeJS](https://nodejs.org/en/)
[CORS](https://www.npmjs.com/package/cors)
[LowDB](https://www.npmjs.com/package/lowdb)

## Features

Current features include the ability to create account, make deposits, withdrawals, and check balance.

Future feature improvements will include adding roles for different users, such as bank employee vs customer with Firebase authentication and authorization. Additional security will be added that only the logged in user can see their own account information. 

## Questions or Comments?

Connect with me on [Twitter](https://twitter.com/kristinedugan) or [LinkedIn](https://linkedin.com/in/kristinedugan).

## License Information

Some implementations and solutions in this project are derived from the provided lectures and materials of MIT xPro's MERN Stack Bootcamp course.

### MIT License

Copyright (c) 2020 John Williams

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
