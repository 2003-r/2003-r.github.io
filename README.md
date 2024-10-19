# 2003-r.github.io
# My Github Profile

## Contributions

### Project 1 - IUShare
- https://github.com/Ilmaooo/IUShare.git
- This project is a web application designed to facilitate collaboration among students by allowing them to share and access academic resources. Developed using React for the frontend and Firebase for the backend, it provides a user-friendly interface for logging in, registering, and uploading files.
- Key Features:
  User Authentication: Implemented the front-end for login and registration pages.
  File Uploading: Designed a file upload interface that allows users to upload notes and materials seamlessly. Utilized Firebase Storage for handling file uploads.
  Top Rated Files: Integrated functionality to fetch and display top-rated files on the home page, enhancing user engagement and resource accessibility.
  Single Note Page: Developed a dedicated page for each uploaded file, allowing users to view and interact with specific notes.
  Search Functionality: Implemented a search bar to help users quickly find specific files based on keywords, improving navigation and user experience.
  This project not only demonstrates my skills in React and Firebase but also showcases my ability to create practical solutions that foster collaboration and resource sharing among students.

### Project 2 - CulinaryConnect 
 - Back-end - https://github.com/2003-r/CulinaryConnect_Backend.git
 - Front-end - https://github.com/elidaarnaut/CulinaryConnect-frontend.git
 - Description:
  This project is a full-stack web application that allows users to share, search, and interact with recipes, built using Node.js and Express.js for the backend, and React for the frontend. The backend provides a secure and efficient RESTful API for managing users, recipes, and interactions within the platform.
  
  Key Features:
  
  User Authentication:
    Implemented secure user authentication using JWT (JSON Web Tokens). Upon successful login, a token is generated and sent to the frontend, where it is stored securely in local storage. This token is included in each request to protect routes, such as managing user profiles. Tokens have an expiration time to ensure they are valid only for a set period, enhancing security.
    
    Password Security:
    Users' passwords are hashed using bcrypt before being stored in the database, ensuring that sensitive information is protected from potential breaches.
  
  CRUD Operations for Recipes:
    Developed full CRUD functionality for recipes, allowing users to:
    
    Create and add new recipes.
    View available recipes.
    Like and unlike recipes.
    Search Functionality:
    Implemented a search bar that allows users to filter recipes based on keywords from titles and ingredients, improving usability and making it easier to find specific recipes.
    
  Security Enhancements:
    Several security measures were taken to protect the application:
    
    NoSQL Injection Prevention: Validated and sanitized user inputs to prevent malicious queries from altering the database.
    Input Sanitization: Added protection against XSS (Cross-Site Scripting) by sanitizing input fields such as recipe names and descriptions.
    Session Management: Used cookies to store session-related information, providing an additional layer of security during user interactions with the server.
  Dockerization:
    The entire web application was dockerized to ensure consistent deployment across different environments, making it easier to maintain and run the application on various systems.
  
  This project highlights my expertise in Node.js, Express.js, React, JWT-based authentication, security best practices, and containerization using Docker, showcasing my ability to build secure, scalable, and user-friendly web applications.

### Project 3 - MyFood-Master
- https://github.com/2003-r/MyFood-Master.git
- Description:
  This project is an extension of an ASP.NET Web API initially developed to manage food items, allowing users to GET, POST, PUT, PATCH, and DELETE food items. As part of an assignment for the Developing Interactive Web Applications course, additional authentication features were implemented, including user registration and login functionality secured by JWT (JSON Web Token) authentication.
  
  Key Features:
  
  Food Item Management:
    
    The Web API provides endpoints for managing food items, allowing clients to retrieve, create, update, partially update, and delete food item records.
    Authentication & User Management:
    
    A new controller was added to handle user registration and login functionalities.
    Password Hashing:
    User passwords are hashed before storage to ensure sensitive information is kept secure.
  
  JWT-Based Authentication:
    Upon successful login, the API generates a JWT token that is sent to the client. This token is stored on the client side and must be included in requests to access protected endpoints.
  
  Login Endpoint:
  
    Returns 401 Unauthorized if the username and password are invalid.
    Returns 404 Not Found if the username does not exist.
    Returns 200 OK along with the generated JWT token if the login is successful.
  Register Endpoint:
  
    Returns 201 Created when a new user is successfully registered.
    Returns 500 Internal Server Error if there is an issue creating the user.
  This project demonstrates my ability to integrate authentication mechanisms into an existing API, using ASP.NET Core, JWT, and best practices for security like password hashing and status code handling for various outcomes.

### Project 4 - Testing-project - 
Automated Search Functionality Testing with Playwright
- https://github.com/Ilmaooo/testing-project.git
- Description:
  This project focuses on testing the search functionality of a web application using Playwright, a Node.js library for browser automation. The tests are designed to verify both valid and invalid search inputs, ensuring that the application behaves as expected in various scenarios.

Key Features:

Testing Framework:
  Implemented tests using Playwright, specifically utilizing the @playwright/test library for structured and reliable test automation.

Test Cases:

  Invalid Search Input Test:
  The test validates the application's response to invalid search queries by entering special characters (e.g., !#$) in the search bar.
  After submitting the query, the test verifies that the appropriate message ("Nema rezultata za tvoj upit.") is displayed, indicating no results were found for the invalid input.
  Valid Search Input Test:
  This test ensures that valid inputs, such as the term "mobitel," produce correct results.
  It simulates user interactions with the search engine, including opening the home page, filling the search bar, and submitting the query.
  The test validates the application's behavior by checking that valid results are returned upon a successful search query.
  Page Object Model (POM):
  Utilized the Page Object Model to organize and manage the test code efficiently. The SearchPage class encapsulates all the search-related actions (e.g., opening the home page, filling the search bar, and verifying results).

Modular Testing:
Separate test files were created to handle valid and invalid search cases:

  search.spec.ts: Verifies the application's response to invalid search inputs.
  searchvalidinput.spec.ts: Verifies the application's handling of valid search queries.
  This project demonstrates my proficiency in using Playwright for end-to-end testing, employing the Page Object Model to maintain clean, reusable, and modular test code. It also showcases my ability to automate UI testing and ensure the reliability of web applications.


 ### Project 5 - Advanced Calculator
  - Project Title: Advanced Calculator with Memory and Error Handling
  - https://github.com/2003-r/Advanced-Calculator.git
  - Description:
  This advanced calculator application goes beyond basic operations like addition, subtraction, multiplication, and division by incorporating features such as:
  
  Remainder Function: Calculates the remainder of integer division.
  Exponentiation: Computes powers (x^n) without using built-in functions, implemented with loops.
  Square Root Calculation: Calculates square roots.
  The calculator allows users to chain operations, retrieve previously saved results, and handle incorrect inputs gracefully without terminating the program. It includes memory functionality where users can save results and retrieve or list them for further use. The project was implemented in Python, JavaScript, and C#, demonstrating cross-language proficiency.
