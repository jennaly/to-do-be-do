# To Do Be Do Be Do 
A minimalistic todo application to document daily chores and errands. Tasks can be readily added, edited, or removed. 

![alt text](https://github.com/jennaly/to-do-be-do/blob/main/public/img/to-do-be-do.gif?raw=true)

## How It's Made:

**Tech used:** <br>
Front-End: HTML, CSS, EJS <br>
Back-End: Node.js, Express.js, MongoDB 

The server is created with Node and Express and connects to a Mongo database. A route is set up to query data from the database. Data is structurally defined with a Mongoose schema and displayed in EJS. Using EJS for form inputs provides front-end functionality without having to use tedious DOM manipulation methods. The server uses the 2 built-in functions in Mongoose - findbyIDAndUpdate() and findbyIDAndDelete() to facilitate changes and removal of documents in the database, and only incorporates the GET and POST HTTP methods in its routing. 

## Lessons Learned:

I learned to create an application with CRUD functionality, replace PUT and DELETE methods with two Mongoose built-in functions, design a schema to streamline data structure, and use EJS to render DOM elements. 




