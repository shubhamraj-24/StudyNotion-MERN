# StudyNotion Edtech Project
<img width="450px;" src="https://github.com/shubhamraj-24/StudyNotion-MERN/blob/main/src/assets/s1.png"/>

StudyNotion is a fully functional ed-tech platform that enables users to create, consume,
and rate educational content. The platform is built using the MERN stack, which includes
ReactJS, NodeJS, MongoDB, and ExpressJS.

StudyNotion aims to provide:

− A seamless and interactive learning experience for students, making education
more accessible and engaging.

− A platform for instructors to showcase their expertise and connect with learners
across the globe.
In the following sections, we will cover the technical details of the platform, including:
1. System architecture: The high-level overview of the platform's components and
diagrams of the architecture.
2. Front-end: The description of the front-end architecture, user interface design,
features, and functionalities of the front-end, and frameworks, libraries, and tools
used.
3. Back-end: The description of the back-end architecture, features and functionalities of
the back-end, frameworks, libraries, tools used, and data models and database schema.
4. API Design: The description of the API design, list of API endpoints, their
functionalities, and sample API requests and responses.

## Installation

### Clone the repository
1. Fork this repository.
2. Clone the repository: `git clone https://github.com/shubhamraj-24/StudyNotion-MERN.git`

### Configure the client

1. Navigate to client folder: `cd client`
2. Install required packages: `npm i`

### Configure the server

1. Navigate to server folder: `cd server`
2. Install required packages: `npm i`
3. Set up the database and configure the environment variables by following the instructions in the next steps.

### Set up the database

1. Create a MongoDb Atlas Account and create a new database.
2. Create a `.env` file in the server folder and add the following environment variables:

```
PORT= <port_to_run_node_server>
MONGODB_URL= <postgres_connection_string>
JWT= <JWT_secret>

```

### Run the application

#### Run the server

1. Navigate to server folder: `cd server`
2. Start Client : `npm start`
3. Server will be running at `http://localhost:8080`

#### Run the client

1. Navigate to server folder: `cd client`
2. Start Client : `npm start`
3. Open the application in your browser at `http://localhost:3000`


In summary, StudyNotion is a versatile and intuitive ed-tech platform that is designed to
provide an immersive learning experience to students and a platform for instructors to
showcase their expertise. In the following sections, we will delve into the technical details
of the platform, which will provide a comprehensive understanding of the platform's
features and functionalities.
