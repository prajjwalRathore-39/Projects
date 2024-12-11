# Demo Application

The application leverages the finctionality of **Docker** containers communnicating with each other. The main functionality of the application is where users can simply see and track there goals.

This Application is container of majorly three parts :- <br>

1. **frontend** - Written in React.js which is majorly a single page application. <br>
2. **backend** - Backend for this mini project is written in node.js, It simple is a Node.js RESTAPI.<br>
3. **database** - The database which powers the application is mongoDB

### Functionalities :

1. **frontend** - The frontend is a **react.js** application, which sends the request to the backend api to **get** the goals set by the user or also to **add** a new goal there, and also to **delete** any goal which is present.
2. **backend** - The present node.js api simply takes a couple of requests that allows the user to set, see and delete goals. In the database there is some logic present to generate the log files and save them in order to see the status of the application at any point of tim.

## Objective

The main objective for the project is to containorize all the three compoments of the project and then make them to cimmunicate with each other inorder to achieve the complete functionality of the project.

1. Create a docker network for effecient cross container communication.
2. Fixing MongoDB authentication erros.
3. Ading data persistence to MongoDB with Volumes.
4. Volumes, Bind Mounts & Polishing for the Node.js Container.
5. Live Source Code updates for the React.js container with Bind Mounts.
6. Data must persist in the database.
