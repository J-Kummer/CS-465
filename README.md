# CS-465
dependencies 
node.js
Visual Studio Code(or any other code editor, if needed)
Git
MongoDB and MongoDB compass
Dbeaver(if not on windows)
Postman

to run locally, download the file travlr. once done open the powershell.
from theor locate the file on your computer.
placement varies computer to computer. 
next use  npm install -g express-generator to install the 
express template generator using the -g switch.
after generate an empty express web application using
express --view=hbs --git --force.
npm install installs node the packages.
to check vulnerabilities use npm audit.
now we can start the web server, using set DEBUG=travlr
from there you can use mpm start to check your web page. 
(you may be asked to allow communications through the firewall, if so press allow)
Open your browser and connect to the following URL: http://localhost:3000, this links to your web page.
(before use, make sure each time to use the powershell to start the node with npm start.)












Architecture 

Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).
We started with Express HTML, this behaved like a traditional webpage. The server sens HTML pages to the browser. It loads each new page or updated content. Javascript makes the frontend interactive, instead of static HTML. It can make respond to users actions and interact with the backend. The SPA framework works different than Express HTML. instead of loading everything each request, it loads majority of the application on start up. This leads to a smoother transition between pages but a slower start time. 

Why did the backend use a NoSQL MongoDB database?
We used MongoDB because it works well with JSON-like structures. It's flexible when data changes and works well with Javascripe, node and Express. 

Functionality 

How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?
Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components. 

JSON is more efficient to use, especially with complex applications. When changing from HTML to Javascript we used Javascripts structure and functions to shorten out our coding. Sections that contained over 160 lines of code were able to be shortened to 36 lines. This made it more compact, reusable and easier to manage. Proof of its efficiency and maintainability are that code snippets could be copied and altered to be reused thanks to its reusable format. JSON ties our frontend and backend tegether because it provides a standard format for our api to send data back and forth. Our testing used Postman to test our API endpoints. I used delete, post, get and put to test our API endpoints. I used PUT to test the edit button and testing my site. Thanks to the RESTful API I was able to test while running my application and it would update when requested. This made testing and error easier to test and fix. 

Testing 

Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing With added layers of security. Explain your understanding of methods, endpoints, and security in a full-stack application. 

For security, we used JWT verification. When we used sensitive information, a token was generated and would be authenticated when a request was sent. If the token was broken or some other issue was presented, an error message would appear. As well as password hashing to protect our information. As well as trust privileges, so only authenticated users could manipulate data. 

Reflection: How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field? This course was challenging and led to a lot of new challenges. We learned how to build a working interactive website. Connect it to a database, added security features, and optimized our code. We learned the importance of small mistakes and how they can upend an entire project, such as a minor misalignment leading to the incorrect placement of a code snippet. Or typos leading to new variables and causing unexpected issues. Troubleshooting and using error messages to correct our code were used extensively. Thanks to this, we can now build and troubleshoot an SPA application confidently. As well as knowing our strengths and weaknesses for any future endeavors. 

