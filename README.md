# CS-465-Full-Stack-Development

## Architecture
* Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).

Express is a back-end web application framework for easily building API's with Node.js. It was used to create the API's for retrieving certain information on a page, such as travlr.com/travel. 
* Why did the backend use a NoSQL MongoDB database?

A NoSQL database is a non-relational database management system. The reason why this one was chosen is because they are very flexible, are good at scaling horizontally, and have high peformance. 

## Functionality
* How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?

The main difference between JSON and JavaScript is that JSON is a data format, and JavaSript is a programming language. JSON stores data in a text-based format. JSON ties together the frontend and backend seamlessly because it is easily understandable by both components. JSON stores data in a key-value pair format, which makes it easy for both components to retrieve and parse the information. JSON is also very common to use for API data retrieval, where the frontend sends a request to the backend, the backend sends a request to the server, it recieves JSON back and sends it to the frontend.

* Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI)

components. Everything that was created provided good functionality, so there was no reason for my to refactor any of it. One of the benefits of using reusable user interfaces is that it can help save a lot of time. If the user interface is the same among multiple pages and the only thing that changes is the data, then it's easy to make a reusable component out of it and just update the data inside. 

## Testing
* Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application.

Security for any kind of application should be the top priority. Defining and implementing codings standards, policies, and methods such as Defense in Depth can help mitigate successful attacks from malicious users. In a full-stack application, endpoints are URL's within an API which provide users access to specific functionalities or resources. Finally, methods are different layers in an application that handle specific tasks. These taks include the frontend, backend, and the database.

## Reflection
* How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?

One of the main things that I learned, which I never though of as highly before, is understanding the importance of security and actively architecting and writing code to adhere to this. Security is more overlooked than it should be, and learning more about the benefits and drawbacks of implementing it, as well as not implementing it, will provide me with good knowledge for future employers. 
