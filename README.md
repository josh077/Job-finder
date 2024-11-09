# MERN Stack job-board-application

This is a job finder web application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It allows users to search for job listings, view job details, and apply for jobs directly through the platform.

## Features

- **User Registration and Login:** Users can create an account and log in to access features.
- **Job Search:** Users can search for job listings based on keywords, location, and other filters.
- **Job Details:** Detailed information about each job, including description, requirements, and application instructions.
- **Job Application:** Users can apply to jobs by submitting their resume and additional required information.
- **Saved Jobs:** Users can save jobs for future reference.
- **User Dashboard:** A personalized dashboard to manage the profile, saved jobs, and job applications.

## Technologies Used

### Front-end
- **React.js:** A JavaScript library for building the user interface.
- **Redux:** Manages the application state predictably.
- **HTML, CSS, and JavaScript:** Core web technologies for building the interface.
- **Axios:** Makes HTTP requests to the server.

### Back-end
- **Node.js:** JavaScript runtime for building server-side applications.
- **Express.js:** Web application framework for Node.js.
- **MongoDB:** NoSQL database for storing job listings and user data.
- **Mongoose:** ODM (Object Data Modeling) library for MongoDB.

### Authentication and Authorization
- **JSON Web Tokens (JWT):** Standard for securely transmitting information between parties as a JSON object.

### Deployment
- **Netlify:** Platform for deploying and hosting the front-end.
- **MongoDB Atlas:** Cloud database service for MongoDB.

## Getting Started

To run the MERN Stack Job Finder project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   https://github.com/josh077/job-board-application.git
   ```
   
2. **Navigate to the project directory:**
   ```bash
   cd mern-job-finder
   ```

3. **Install the dependencies:**
   - Front-end:
     ```bash
     cd client && npm install
     ```
   - Back-end:
     ```bash
     cd server && npm install
     ```

4. **Set up the environment variables:**
   - Create a `.env` file in the server directory.
   - Add the following environment variables:
     ```plaintext
     MONGODB_URI=<Your MongoDB connection string>
     JWT_SECRET=<Your JWT secret key>
     ```

5. **Start the development server:**
   - Front-end:
     ```bash
     cd client && npm start
     ```
   - Back-end:
     ```bash
     cd server && npm start
     ```

6. **Access the application:**
   Open your browser and navigate to `http://localhost:8800`.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.

## Contact

For any inquiries or questions, please contact me <a href="mailto:joshuabunty27@gmail.com">here</a>
.

## Acknowledgements

- Create React App
- React Redux
- Express.js
- MongoDB
- Passport.js

## About

This is a job finder web application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It allows users to search for job listings, view job details, and apply for jobs.

**[Live Demo]((https://glittering-souffle-8e3568.netlify.app/about-us))**


## Languages

- JavaScript 98.0%
- CSS 1.7%
- HTML 0.3%

---

This README provides a comprehensive overview of the application, guiding users through the setup and highlighting the features and technologies used.
