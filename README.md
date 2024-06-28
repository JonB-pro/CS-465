# CS-465
## Full Stack Development 1

### Architecture

For this application, HTML and javascript were used to display pages through Express. This allowed users to load pages quickly as they were requested. For the administrative side a Single-Page Application was built in Angular as a quicker way for admins to access and edit content on the site. The backend implemented a NoSQL MongoDB database, as this storage system works well with JSON and NodeJS, the software used to run the server.

### Functionality

JSON is used for data storage and Javascript for manipulation. Because MongoDB storage can be translated to and from JSON and the frontend programs can read it as well, it is a good connector between both sides of the application. Refactoring the code led to using Handlebars instead of plain HTML, which allowed re-use of certain componants like the header and footer for each page. The benefit of reusable UI is that it does not have to be re-created for each new page added to the application.

### Testing

Testing of methods, endpoints, and security is important in full stack application creation. Methods are how you interact with the data provided by the endpoint, security is how the data is protected from unwanted access, and the endpoint itself details how the data is accessed. In this case, methods allow display and manipulation of the data at the travel endpoint and security is implemented to control who can add, delete, or uptdate the data displayed there.

### Reflection

This course has taught me how to make an application that has a database connected to it, and doesn't look like it was made in 1997. Before this course I had never used Javascript before, and MongoDB was still new to me. I feel like I somewhat understand the first two now, and MongoDB makes a bit more sense. Also, now I know about Postman and Studio3T, which are both very helpful tools.
