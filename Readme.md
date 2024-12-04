# VRV Security
## Backend Developer Intern Assignment


#### Installation 

- Clone the repository
```bash
git clone git@github.com:Swapnil-2502/VRV-Security-Backend-Assignment.git
```
- Next step
```bash
npm install
OR
npm install express nodemon jwtwebtoken cookie-parser
```
- Make a Database at your local MongoDB Compass give a Database Name and Cluster Name as users. Replace '/VRVSecurity' with the name of your Database and you will be connected to MongoDB.
```bash
//Connect to mongoDB using mongoose
connectMongoDB("mongodb://127.0.0.1:27017/VRVSecurity");
```
- Start your local server
```bash
npm run dev
```
- Now you are good to go.Paste this url in your browser "http://localhost:8001/user/login".
I have added /user and /assignment for better understanding but it can be removed if you want it to be.
  
#### Technologies Used

-   ##### Frontend: HTML, CSS, JavaScript
    
-   ##### Backend: Node.js, Express.js
    
-   ##### Database: MongoDB
    
-   ##### Authentication: JWT (JSON Web Tokens) for secure authentication
