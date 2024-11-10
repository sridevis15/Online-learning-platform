# ONLINE LEARNING PLATFORM USING MERN STACK

# INTRODUCTION

An **Online Learning Platform (OLP)** is a digital platform that provides a variety of tools and resources to facilitate learning and education over the internet. These platforms have become increasingly popular, especially in recent years, as they offer flexibility and accessibility for learners of all ages and backgrounds. Here are some key features and a description of an online learning platform:

# PURPOSE

The purpose of the Online Learning Platform (OLP) is :

- To provide a centralized online platform that facilitates flexible, self-paced learning, accessible to users worldwide.

- To enable users to enroll in courses, track learning progress, and earn certifications, supporting personal and professional development.

- To offer an interactive and user-friendly interface that allows learners to navigate content easily and engage in discussion forums, live webinars, and assignments.

- To provide instructors with a streamlined system for creating, organizing, and managing course content effectively.  To allow administrators to monitor platform operations, manage user activities, and ensure data security and integrity.

- To create a scalable, efficient, and cost-effective solution for educational institutions and independent educators looking to deliver content online.
  
# SCOPE

- **User-Friendly Interface:** Online learning platforms typically have an intuitive and user-friendly interface that makes it easy for learners, regardless of their technical proficiency, to navigate and access the content.

- **Course Management:** Instructors or course creators can upload, organize, and manage course materials. Learners can enroll in courses and track their progress.

- **Interactivity:** Many platforms include interactive elements like discussion forums, chat rooms, and live webinars, which foster communication and collaboration among learners and instructors.

- **Certification:** Learners can earn certificates or badges upon completing courses or meeting certain criteria, which can be valuable for employment or further education.

- **Accessibility:** Content is often accessible on various devices, including computers, tablets, and smartphones, making learning possible from anywhere with an internet connection.

- **Self-Paced Learning:** Learners can typically access course materials at their own pace. This flexibility allows for learning that fits into individual schedules and preferences.

- **Payment and Subscription Options:** There may be free courses, but some content may require payment or a subscription. Platforms often offer multiple pricing models.


# SCENARIO BASED CASE STUDY
 
- **User Registration:** Sarah, a student interested in learning web development, visits the Online Learning Platform and creates an account. She provides her email and chooses a password.

- **Browsing Courses:** Upon logging in, Sarah is greeted with a user-friendly interface displaying various courses categorized by topic, difficulty level, and popularity. She navigates through the course catalog, filtering courses by name and category until she finds a "Web Development Fundamentals" course that interests her.

- **Enrolling in a Course:** Sarah clicks on the course and reads the course description, instructor details, and syllabus. Impressed, she decides to enroll in the course. After enrolling, Sarah can access the course materials, including video lectures, reading materials, and assignments.

- **Learning Progress:** Sarah starts the course and proceeds through the modules at her own pace. The platform remembers her progress, allowing her to pick up where she left off if she needs to take a break.

- **Interaction and Support:** Throughout the course, Sarah engages with interactive elements such as discussion forums and live webinars where she can ask questions and interact with the instructor and other learners.

- **Course Completion and Certification:** After completing all the modules and assignments, Sarah takes the final exam. Upon passing, she receives a digital certificate of completion, which she can download and add to her portfolio.

- **Paid Courses:** Sarah discovers an advanced web development course that requires payment. She purchases the course using the platform's payment system and gains access to premium content.

- **Teacher's Role:** Meanwhile, John, an experienced web developer, serves as a teacher on the platform. He creates and uploads new courses on advanced web development topics, adds sections to existing courses, and monitors course enrollments.

- **Admin Oversight:** The admin oversees the entire platform, monitoring user activity, managing course listings, and ensuring smooth operation. They keep track of enrolled students, handle any issues that arise, and maintain the integrity of the platform.

# TECHNICAL ARCHITECTURE

- The technical architecture of OLP app follows a client-server model, where the frontend serves as the client and the backend acts as the server. The frontend encompasses not only the user interface and presentation but also incorporates the axios library to connect with backend easily by using RESTful Apis.

- The frontend utilizes the bootstrap and material UI library to establish real-time and better UI experience for any user.

- On the backend side, we employ Express.js frameworks to handle the server-side logic and communication. 

- For data storage and retrieval, our backend relies on MongoDB. MongoDB allows for efficient and scalable storage of user data and necessary information about the place.

- Together, the frontend and backend components, along with Express.js, and MongoDB, form a comprehensive technical architecture for our OLP app. This architecture enables real-time communication, efficient data exchange, and seamless integration, ensuring a smooth and immersive blogging experience for all users.

# SYSTEM REQUIRMENTS

**HARDWARE**
-
- **Operating System :** Windows 8 or higher
  
- **RAM :** 4 GB or more (8 GB recommended for smooth development experience)
  
**SOFTWARE**
-
- **Node.js :** LTS version for back-end and front-end development
  
- **MongoDB :** For database management using MongoDB Atlas or a local instance
  
- **React.js :** For front-end framework
  
- **Express.js :** For back-end framework
  
- **Git :** Version control
  
- **Code Editor :** e.g., Visual Studio Code
  
- **Web Browsers :** Two web browsers installed for testing compatibility (e.g., Chrome and Firefox)
  
**NETWORK**
-
- **Bandwidth :** 30 Mbps

# TECH STACKS

The tech stacks used here are:
-
- **Mongo DB**
- **Express.js**
- **Node.js**
- **React.js**

# Installation

- **Vite**

  npm create vite@latest
  
- **Node.js**

  Download: https://nodejs.org/en/download/

  Installation instructions: https://nodejs.org/en/download/package-manager/

  Run “npm init” to get default dependencies

- **Express.js**

  npm install express

- **Mongo DB**

  Download: https://www.mongodb.com/try/download/community

  Installation instructions: https://docs.mongodb.com/manual/installation/

- **React. js**

  https://reactjs.org/docs/create-a-new-react-app.html

# Application Flow

The project has a user called– teacher and student and other will be Admin which takes care of all the user. The roles and responsibilities of these users can be inferred from the API endpoints defined in the code. Here is a summary: 

**Teacher:**
-
- Can add courses for the student.

- Also delete the course if no student enrolled in it or any other reasons.

- Also add sections to courses.

**Student:**
-
- Can enroll in an individual or multiple course.

- Can start the course where it has stopped.

- Once the course is completed, they can download their certificate of completeion of the course.

- For paid course, they need to purchase it and then they can start the course.

- They can filter out the course by searching by name, category, etc


**Admin:**
-
- They can alter all the course that are present in the app.

- Watch out all kind of users in app.

- Record all the enrolled all the student that are enrolled in course.

# PROJECT IMPLEMENTATION

We install following dependencies for frontend they are:

- React, Material UI, Bootstrap, React - bootstrap, Axios, Antd, Mdb-react-ui-kit

We install following dependencies for backend they are:

- Cors, bcryptjs, multer,dotenv, Express, mongoose, nodemon, jsonwebtoken

# PROJECT EXECUTION

On completing the development part, we then run the application one last time to verify all the functionalities and look for any bugs in it. The user interface of the application looks a bit like the one’s provided below.

1. For Frontend, we use to run with the following command respectively

  - cd frontend
  - npm install
  - npm run dev

2. For Backend, we use to run with the following command respectively

  - cd backend
  - npm install
  - npm start

The OLP app will be accessible at http://localhost:5172

# CONCLUSION

The conclusion of this project focuses on integrating a full-stack application, combining a React front end with a Node.js and Express back end, connected to a MongoDB database. By implementing modular code structure, secure authentication, and efficient data handling, this project successfully delivers an online learning platform (OLP) that allows different user roles—admin, teacher, and student—to manage and access course-related functionalities. Through the integration of various tools and libraries like Axios for HTTP requests, Multer for handling file uploads, JWT for authentication, and Mongoose for database management, the platform provides a seamless and responsive user experience. 

Additionally, security measures, such as using bcryptjs for password hashing and CORS for controlling cross- origin access, enhance the robustness and integrity of the system. In conclusion, this project showcases an effective implementation of a scalable and interactive learning management system by utilizing modern web development practices and technologies. It serves as a foundation for further enhancements, such as incorporating additional features, refining the user interface, or optimizing performance for large-scale deployment.

# SCREENSHOTS OF THE INSTALLATIONS & PROJECT EXECUTIONS

**Doc Link :** https://github.com/sridevis15/Online-learning-platform/blob/main/Screenshots%20of%20Installation%20and%20Execution.pdf
