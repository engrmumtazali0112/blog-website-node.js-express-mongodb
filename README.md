# Blog Website

# A dynamic, full-stack blog website built with Node.js, Express, and MongoDB.

## Features
- User authentication (register, login, logout)
- Create, read, update, and delete blog posts
- Upload images for blog posts
- Admin dashboard for managing users and posts
- Responsive design for mobile and desktop


 ![1](https://github.com/user-attachments/assets/b0516a13-937a-488d-a97c-0b8358cd3a03)
 ![2](https://github.com/user-attachments/assets/b0c26401-5a09-42c3-b4e8-f5165f3e641c)
 ![3](https://github.com/user-attachments/assets/6a711cd9-5be7-4f03-92c5-0342923936be)
![4](https://github.com/user-attachments/assets/b5a464ff-6417-4628-b8d5-2e4a45174552)
![5](https://github.com/user-attachments/assets/086d9c0a-e763-4382-8688-9d456d00e57f)
![6](https://github.com/user-attachments/assets/f0ac6a2d-021e-4f1e-87ce-e224d9f1cb13)
![7](https://github.com/user-attachments/assets/642b4868-f3d6-4d3c-b2a5-7de8b36444a8)
![8](https://github.com/user-attachments/assets/e6a1d128-589f-4163-8f51-993b8339e88b)
![9](https://github.com/user-attachments/assets/3af8f3b4-b2b9-4c88-8f28-5ecc7eef90c3)








# **# Technologies Used**

- **Node.js**: JavaScript runtime for server-side development
- **Express.js**: Web application framework for Node.js
- **MongoDB**: NoSQL database for storing blog posts and user information
- **Mongoose**: ODM (Object Data Modeling) library for MongoDB and Node.js
- **EJS**: Templating engine for generating HTML with JavaScript
- **bcrypt**: Library for hashing passwords
- **express-session**: Middleware for handling user sessions
- **multer**: Middleware for handling multipart/form-data, used for file uploads
- **method-override**: Middleware to use HTTP verbs such as PUT or DELETE
- **body-parser**: Middleware to parse incoming request bodies


Admin dashboard for managing users and posts
Responsive design for mobile and desktop

# Project Structure


│

├── config/

│   └── db.js

│

├── models/

│   ├── Post.js

│   └── User.js

│

├── public/

│   ├── css/

│   ├── js/

│   └── uploads/

│

├── routes/

│   ├── auth.js

│   └── postRoutes.js

│

├── views/

│   ├── partials/

│   │   ├── header.ejs

│   │   └── footer.ejs

│   ├── about.ejs

│   ├── contact.ejs

│   ├── create-edit-post.ejs

│   ├── dashboard.ejs

│   ├── index.ejs

│   ├── layout.ejs

│   ├── login.ejs

│   ├── posts.ejs

│   ├── register.ejs

│   └── show.ejs

│

├── .gitignore

├── app.js

├── package.json

└── README.md


# **Setup and Installation**

Clone the repository:
git clone [https://github.com/engrmumtazali0112/blog-website-node.js-express-mongodb](url)
cd blog-website

# **Install dependencies:
npm install**

# **Set up environment variables:**
Create a .env file in the root directory and add the following:
MONGODB_URI=your_mongodb_connection_string
SESSION_SECRET=your_session_secret

Start the server:
npm start

# Open your browser and navigate to [http://localhost:3000](url)



**API Endpoints**

- GET /: Home page
- GET /posts: View all posts
- GET /posts/:id: View a specific post
- POST /posts: Create a new post (authentication required)
- PUT /posts/:id: Update a post (authentication required)
- DELETE /posts/:id: Delete a post (authentication required)
- GET /dashboard: Admin dashboard (admin authentication required)

**Contributing**

Fork the repository
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a pull request

**License**
This project is licensed under the MIT License - see the LICENSE.md file for details
Acknowledgments

Hat tip to anyone whose code was used
Inspiration
etc

## Contact
Made with ❤️ by Mumtaz Ali | [LinkedIn](https://www.linkedin.com/in/mumtaz-ali) | [GitHub](https://github.com/engrmumtazali0112)
<div align="center">
<h3> Connect with me
</h3> 
<p align="center">
    <a href="mailto:engrmumtazali01@gmail.com" target="_blank"><img alt="Gmail" width="25px" src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Gmail.svg"></a> 
    <a href="https://www.linkedin.com/in/mumtazali12/" target="_blank"><img alt="LinkedIn" width="25px" src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Linkedin.svg"></a>
    <a href="https://www.instagram.com/its_maliyzi?igsh=MWR1Y2x1a2xpazBpOA==" target="_blank"><img alt="Instagram" width="25px" src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Instagram.svg"></a>
    <a href="https://www.hackerrank.com/profile/engrmumtazali01" target="_blank"><img alt="HackerRank" width="25px" src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/HackerRank.svg"></a>
    <a href="https://github.com/engrmumtazali0112" target="_blank"><img src="https://cdn.svgporn.com/logos/github-icon.svg" alt="Github logo" width="25px"></a>
</p>  


