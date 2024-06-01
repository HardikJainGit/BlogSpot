
# BlogSpot - Blog Writing & Sharing Platform



## Table of Contents
* [About BlogSpot](#about-blogspot)
* [Key Features](#key-features)
* [More Features](#more-features)
* [Tech Stack Used](#tech-stack-used)
* [Installation](#installation)
* [Images of Working App](#images-of-working-app)


## About BlogSpot
BlogSpot is a platform designed to empower you to express your thoughts, ideas, and stories through blogging. This is a basic Node.js and Express.js application of a blogs website where MongoDB is used to store all the blogs.

## Key Features
#### View latest Blogs

#### Can Register and Do Admin Sign-in

#### Create your blogs

#### View any blog

#### Update your blogs

#### Delete your blogs

#### Search any blog

#### MongoDB Atlas used to store the blogs , usernames and passwords

## More Features
Latest Blogs available on first page ; can view older blogs also. Admins can register their accounts ; data is stored in MongoDB Atlas. The registered admins can login to see the blogs and perform CRUD (Create, Read, Update, Delete) operations on them ; these operations are reflected on the MongoDB server. JWT (JSON Web Token) authentication and authMiddleware were implemented in the project to handle user authentication , it automatically logs out an admin if their authentication tokens are deleted or become invalid. Also implemented Logout functionality.

## Tech Stack Used
- HTML
- CSS
- JavaScript
- EJS
- Node.js
- Express
- MongoDB
- Mongoose ODM

## Installation

- Clone the repository by opening your terminal and navigating to the directory where you want to clone the repository. Then, run the following command:
```bash
  git clone https://github.com/HardikJainGit/BlogSpot.git
```

- Navigate to the App Directory:
```bash
  cd BlogSpot
```

- Install the required dependencies using npm package manager:
```bash
  npm install
```
- Start the development server:
```bash
  npm start
```
- Access the website by visiting 'http://localhost:5000' 

## Video of Working App



https://github.com/HardikJainGit/BlogSpot/assets/133627261/d129e777-3a4b-4c14-b1d1-e095cb6a6b05


