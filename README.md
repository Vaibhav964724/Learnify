Learnify is a full-stack course management platform that simplifies the process of creating, managing, and purchasing online courses. Built with the MERN stack (MongoDB, Express.js, React.js, Node.js), it offers dedicated interfaces for both administrators and learners.


# Table of Contents

1. [Admin Panel](#admin-panel)
2. [User Panel](#user-panel)
3. [Demo video](#demo-video)
4. [Developed using](#developed-using)
5. [Quick Start](#quick-start)
6. [Contributing](#contributing)
7. [License](#license)


## Admin Panel

1. Accessing the admin section of the course-selling app.
2. Admins can effortlessly log in or create a new account.
3. All administrators have the authority to:
   ✅ CREATE courses
   ✏️ UPDATE courses
   ❌ DELETE courses

## User Panel

1. Exploring the learner interface of the course-selling app.
2. Learners can easily log in or register a new account.
3. Users have the opportunity to explore and acquire knowledge from a diverse array of courses.
4. Users can smoothly make purchases for their desired courses!💡

Note: The payment system and course content uploading features are currently under development.

## Demo video


## Developed Using

1. React.js
2. Node.js
3. Express.js
4. MongoDB
5. CSS3
6. MUI
7. Vite.js

## Quick Start

To set up a local copy of CourseHub, follow these simple steps:

## Prerequisites

Ensure that Node.js and npm are installed on your machine.

## Development

1. Fork the repository to your profile.
2. Clone your repository by running the following command in your terminal:
   ```sh
   git clone <your-repository-url>
   ```

### Server Setup

1. Change directory to the root of the cloned repository
   ```sh
   cd Learnify-main
   ```
2. Change directory to the server folder
   ```sh
   cd server
   ```
3. Install the required npm packages
   ```sh
   npm install
   ```
4. Create .env file and add DB_NAME and SECRET
   ```sh
   DB_CONNECT = mongodb://localhost:27017/project
   SECRET = "Random String";
   ```
5. Start the server
   ```sh
   npm start
   ```

### Admin Client Setup

1. Change directory to the Client-Admin folder
   ```sh
   cd ../Client-Admin
   ```
2. Install the required npm packages for the admin client
   ```sh
   npm install
   ```
3. Run the admin client in development mode
   ```sh
   npm run dev
   ```

### User Client Setup

1. Change directory to the Client-user folder
   ```sh
   cd ../Client-user
   ```
2. Install the required npm packages for the admin client
   ```sh
   npm install
   ```
3. Run the admin client in development mode
   ```sh
   npm run dev
   ```
#licence
