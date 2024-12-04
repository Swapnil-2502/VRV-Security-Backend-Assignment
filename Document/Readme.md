
# VRV Security

## Backend Developer Intern Assignment

This document will help you go through the assignment using screenshot for better understanding.

**Objective** => The goal of this assignment is to assess your understanding and implementation skills regarding Authentication, Authorization, and Role-Based Access Control (RBAC).

**Assignment** => I have created a submission portal where a user can submit an assignment tagging an admin which can later 'Accept' or 'Reject' the assignment.

 1. Register Page
    This is the registration page for the user where if you tick the checkbox you will be register as role of 'ADMIN' and by default role will be 'USER'
    ![alt text](<Screenshot 2024-12-04 at 5.00.32 PM.png>)

 2. Login Page
    After registration you will be redirected to this page. You need to fill your email and password for successful login it will show error in case you fail to do it.
    ![alt text](<Screenshot 2024-12-04 at 5.06.10 PM.png>)

 3. Home Page
    After login you will se Home page which would be empty as the 'USER' didn't upload any assignment.

 4. Upload Assignment
    Here you can upload an assignment. Without correct Username and Admin name the assignment will not get submitted(will throw an error). And you will be directed to home page showing you assignment with current status as 'Pending'. The status update once the 'ADMIN' will 'Accept' or 'Reject' your assignment.
    ![alt-text-1](<Screenshot 2024-12-04 at 5.18.49 PM.png>)![alt-text-2](<Screenshot 2024-12-04 at 5.19.00 PM.png>)