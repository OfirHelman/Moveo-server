##Real-Time Code Collaboration System - Server##

This project is the server-side component of a real-time code collaboration system built using React, Express, and Socket.io. It facilitates communication between clients, manages user roles, and coordinates real-time updates to code blocks.

***Installation***

Clone the repository to your local machine:

bash
Copy code
git clone <repository_url>
Navigate to the server directory:

bash
Copy code
cd server
Install dependencies:

bash
Copy code
npm install
Usage
Start the server:

bash
Copy code
npm start
Open your web browser and navigate to the provided URL. By default, the server will run on port 5001.

***Features***

Real-time communication: Utilizes Socket.io to enable real-time communication between clients, ensuring that changes made by any user are instantly reflected for all others viewing the same code block.

Role-based access control: Assigns users roles (mentor or student) upon connection. Mentors have read-only access to the code, while students can edit it.

Dynamic role assignment: Automatically assigns the mentor role to the first user to join a code block. Subsequent users joining the same code block are assigned the student role.

***Configuration***

CORS: Cross-Origin Resource Sharing (CORS) is enabled to allow requests from the client-side application running on http://localhost:3000. You can adjust the origin as needed in the CORS configuration.
