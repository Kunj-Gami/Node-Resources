# 📘 Question Bank: Node.js

## 1. Node.js Basics
1. What is Node.js, and how does it work?
2. What are the main differences between Node.js and traditional server-side programming languages like PHP or Python?
3. Explain the concept of non-blocking I/O in Node.js.
4. How does Node.js handle concurrency and asynchronous operations?
5. What is the event loop in Node.js, and how does it work?
6. What are the key features of Node.js?
7. What is npm (Node Package Manager), and how is it used in Node.js development?
8. What is a package.json file, and what is its significance in a Node.js project?
9. How do you create a simple HTTP server in Node.js?
10. What are streams in Node.js, and how do they work?

## 2. Node.js Modules
11. What are modules in Node.js?
12. How do you import and export modules in Node.js?
13. What are built-in Node.js modules, and how do you use them?
14. How does the `fs` (file system) module work in Node.js?
15. What is the `path` module in Node.js, and how is it used to work with file and directory paths?
16. What is the `os` module in Node.js, and how can it be used to gather operating system information?
17. How does the `http` module work in Node.js to create an HTTP server?
18. What is the `url` module in Node.js, and how does it help in URL parsing and manipulation?
19. What is the `crypto` module in Node.js, and how can it be used for encryption?
20. How can you manage dependencies using npm in Node.js?

## 3. Asynchronous Programming
21. What is the difference between synchronous and asynchronous programming?
22. What are callbacks in Node.js, and how are they used?
23. How do you handle errors in asynchronous callbacks in Node.js?
24. What are Promises in Node.js, and how are they used?
25. How does async/await work in Node.js, and how does it help simplify asynchronous code?
26. How do you handle multiple asynchronous operations in parallel in Node.js?
27. What is the `EventEmitter` class in Node.js, and how does it work?
28. How do you emit and listen to events in Node.js?
29. How does the `setTimeout()` and `setInterval()` functions work in Node.js?
30. How does the `process.nextTick()` function differ from `setImmediate()`?

## 4. Express.js Framework
31. What is Express.js, and why is it commonly used with Node.js?
32. How do you set up a basic Express.js application?
33. What is middleware in Express.js, and how is it used?
34. How do you handle HTTP requests (GET, POST, PUT, DELETE) in Express.js?
35. How do you handle query parameters in Express.js routes?
36. What is the `body-parser` middleware in Express.js, and how do you use it to handle form data?
37. How do you set up static file serving in an Express.js application?
38. What is routing in Express.js, and how do you define routes for different HTTP methods?
39. How do you handle errors in Express.js applications?
40. What is the `next()` function in Express.js, and how is it used in middleware?

## 5. Working with Databases
41. How do you connect Node.js to a MongoDB database?
42. What is Mongoose, and how does it help in working with MongoDB in Node.js?
43. How do you perform CRUD (Create, Read, Update, Delete) operations in MongoDB using Mongoose?
44. How do you validate data before saving it to a MongoDB database using Mongoose?
45. How do you handle database queries asynchronously in Node.js?
46. What is the difference between SQL and NoSQL databases, and when should you use each with Node.js?
47. How do you connect Node.js to a MySQL database using a library like `mysql2` or `sequelize`?
48. What are migrations in databases, and how do you handle them in Node.js applications?
49. How do you protect sensitive data like passwords before storing them in the database?
50. How do you handle database connections pooling in Node.js?

## 6. Authentication and Security
51. How do you implement user authentication in Node.js using JWT (JSON Web Tokens)?
52. What are the common authentication strategies used in Node.js applications?
53. How do you hash passwords using bcrypt in Node.js?
54. How do you manage sessions in Node.js for authentication?
55. How do you secure sensitive data in Node.js applications?
56. What is CORS (Cross-Origin Resource Sharing), and how do you handle it in Node.js?
57. How do you prevent SQL injection in Node.js applications?
58. How do you handle cross-site scripting (XSS) attacks in Node.js?
59. How do you implement role-based access control (RBAC) in Node.js applications?
60. What is the purpose of environment variables, and how do you manage them securely in Node.js?

## 7. File Handling in Node.js
61. How do you read files synchronously and asynchronously in Node.js using the `fs` module?
62. How do you write files asynchronously in Node.js?
63. How do you append data to a file in Node.js?
64. What is the `stream` module, and how do you use it to handle large files efficiently in Node.js?
65. How do you delete files using the `fs` module in Node.js?
66. How can you watch for file changes using the `fs.watch()` method in Node.js?
67. How do you handle file uploads in Node.js?
68. How do you handle directories and file paths using Node.js?
69. How do you move or rename files in Node.js?
70. What is file system locking in Node.js, and when is it necessary?

## 8. WebSockets and Real-Time Applications
71. What is WebSocket, and how is it used in Node.js for real-time communication?
72. How do you set up a WebSocket server in Node.js using the `ws` library?
73. How do you send messages from the server to the client using WebSockets in Node.js?
74. How do you implement a simple chat application using WebSockets in Node.js?
75. What is the difference between WebSockets and HTTP in terms of communication in Node.js?
76. How do you handle disconnections and reconnections with WebSockets in Node.js?
77. What are the benefits of using WebSockets in real-time applications?
78. How do you use Socket.io with Node.js to create real-time web applications?
79. How do you authenticate WebSocket connections in Node.js?
80. How do you broadcast messages to all connected clients in a WebSocket server?

## 9. Performance Optimization
81. How do you profile and optimize the performance of a Node.js application?
82. What are the common performance bottlenecks in Node.js applications?
83. How do you handle large amounts of data efficiently in Node.js applications?
84. How do you reduce memory usage in Node.js applications?
85. What is the purpose of the `cluster` module in Node.js, and how does it help scale applications?
86. How do you handle load balancing in Node.js applications?
87. What is the `pm2` process manager, and how does it help in managing Node.js applications in production?
88. How do you handle caching in Node.js applications to improve performance?
89. How do you manage session persistence in a Node.js application for scalability?
90. What are best practices for error handling and debugging in production for Node.js applications?

## 10. Testing and Debugging
91. How do you write unit tests for Node.js applications?
92. What testing frameworks are commonly used with Node.js (e.g., Mocha, Jasmine, Jest)?
93. How do you test asynchronous code in Node.js using testing frameworks?
94. What is the purpose of mocking in Node.js tests, and how is it implemented?
95. How do you debug Node.js applications using the `node --inspect` flag?
96. How do you use the `assert` module in Node.js for testing purposes?
97. How do you perform integration testing in Node.js applications?
98. What is code coverage, and how do you measure it in Node.js applications?
99. How do you handle end-to-end testing for Node.js APIs?
100. What is Test-Driven Development (TDD), and how is it implemented in Node.js?

