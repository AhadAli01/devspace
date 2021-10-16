# Project: DevSpace

Live Demo: https://ahad-devspace.herokuapp.com/

### About
***
This project was a full stack application that utilizes the MERN (MongoDB, Express, React, Node.js) stack to create a social networking application (like MySpace) but excusively for developers. Users can sign up for an account, create a developer profile/portfolio, share posts and get help from other developers.

### Key Learnings
***
This project helped me gain experience with designing and developing a full stack project using the MERN stack. Some practical concepts I explored included ES6 syntax, Asynchronous JavaScript, creating responsive frontend views with state management using React, Bootstrap, Redux and creating a RESTful API that reads and writes data to a cloud database using Node.js, Express, MongoDB/Mongoose/Atlas, Postman and more.

### Usage
*** 
[Live Demo](https://ahad-devspace.herokuapp.com/)

To tinker with the code and start your own localhost server, simply clone repository and then you need to set a default.json file under the config folder to set up the config variables as shown below
```json
{
  "mongoURI": "<your_mongodb_uri>",
  "jwtSecret": "<yoursecret>",
  "githubToken": "<yoursecrectaccesstoken>"
}
```
 and then type 
```bash
npm install
cd client
npm install
``` 
to install all necessary node modules as specified in package.json and then
```bash
npm run dev
```
to run both the backend (on localhost:5000) and the frontend (on localhost:3000).
