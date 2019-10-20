# Book-your-Vacation
A web application to book condos and townhouses on vacation spots. An exact simulation of HomeAway website. Multi step improval of the technology stack.


## React + Node.js + MySQL
- The first version of the full stack application
- Front-end was supported by React with basic class based components to reduce the redundancy
- Express-sessions were used to maintain user sessions
- Rest APIs with axios requests were used to make a call from front-end server to back-end server
- The node server was connected to MySQL database 


## Redux + React + Node.js + Passport.js + Kafka + MongoDB
- This was the second version of the full stack application. The project now had Redux state management middleware thus solving the problem of state transfer between child and parent components 
- Passport.js was used for making the application more secure by adding JSON web tokens and also adding cryptography for the passwords saved in database
- Leveraged Kafka to manage the communication between client and server. This required the 
  application to be divided into services which had unique topics assigned to them. 
- Lastly, replaced the MySQL database with MongoDB to enhance scalability. Deployed this application 
  on Amazon cloud using 2 EC2 instances.
