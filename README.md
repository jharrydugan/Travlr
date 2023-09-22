# Travlr

Travlr is a RESTful web application designed for vacation bookings and reviews. It was created to cater to the needs of Travlr Getaways, a fictional client with two distinct user bases: administrators and customers. The customer-facing side prioritizes content, emphasizing fast initial load times and shorter user sessions. In contrast, the administrator interface is feature-rich, demanding increased user interaction, a fast and responsive user experience (UE), and longer user engagement.

## Depth of Project

The primary objective of this project was to develop a functional prototype for a full-stack web application using MEAN (MongoDB, Express.js, Angular, Node.js) technologies and the MVC (Model-View-Controller) architectural pattern.

### Backend

Travlr's backend leverages Node.js and the Express framework to power its web server. Data is stored in a NoSQL database called MongoDB, with data modeling facilitated by the Mongoose library.

### Frontend

For the customer-facing frontend, a templating engine is utilized alongside Express.js to dynamically generate HTML in response to requests. In contrast, the administrator's frontend is designed as a Single Page Application (SPA) and is delivered using Angular.

### Security

Security is a paramount concern for Travlr. API endpoints are safeguarded through authentication and authorization mechanisms employing JSON web tokens (JWTs). When a user's credentials are validated, a JWT is issued and stored in their browser's local storage. On the backend, user passwords are securely stored using one-way encryption and are never stored in plaintext.

## The MEAN Stack

- **MongoDB** -  This NoSQL database system is renowned for its speed and flexibility compared to more structured SQL databases. MongoDB's use of BSON and JSON aligns perfectly with the MEAN stack's emphasis on JSON and JavaScript.
- **Express** - Express, a Node.js framework, simplifies the development of Node applications. It works in tandem with Handlebars to template and dynamically render HTML pages.
- **Angular** - Angular serves as the frontend framework that facilitates Single Page Applications (SPAs). This architecture minimizes server requests after the initial page load, enhancing responsiveness. However, it may impact search engine indexing due to the limited initial page content.
- **Node.js** - The foundation of this project's web server, Node.js is a versatile platform for modern web application development. Utilizing JavaScript as the primary programming language for both Node and Express, the MEAN stack streamlines development by requiring proficiency in a single language.




