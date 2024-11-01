
# SocialEcho

A social networking platform with automated content moderation and a context-based authentication system.

![WhatsApp Image 2024-11-01 at 3 42 26 PM](https://github.com/user-attachments/assets/25136041-2cfe-48b4-8058-1118cd896568)

## Project Overview

SocialEcho is a social networking platform built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It incorporates two major features: an automated content moderation system and context-based authentication. Users can enjoy standard social media functionalities, such as profile creation, post creation and sharing, liking and commenting on posts, and following/unfollowing users.


## Tech Stack

### Frontend
- **React.js**
- **Redux**
- **Tailwind CSS**

### Backend
- **Node.js**
- **Express.js**
- **MongoDB**

### Authentication & Security
- **JWT Authentication**
- **Passport.js**
- **Crypto-js** (for data encryption)

### Content Moderation
- **Flask** (for running the BART Large MNLI model)
- **Hugging Face Transformers**
- **Perspective API**
- **TextRazor API**

### Additional Tools
- **Nodemailer** (for email notifications)
- **Azure Blob Storage** (for file storage)

## Key Features
- User authentication and authorization (JWT)
- User profile creation and management
- Post creation and management
- Commenting on posts
- Liking posts and comments
- Following/unfollowing users
- Reporting inappropriate posts
- Automated content moderation using NLP APIs
- Context-based authentication for enhanced security
- Device management for user accounts
- Admin dashboard for system management
- Moderator dashboard for community oversight
- Email notifications for suspicious login attempts
![WhatsApp Image 2024-11-01 at 3 45 31 PM](https://github.com/user-attachments/assets/25ca8440-23e6-47ed-a1da-86aa3f06bf73)

## Getting Started

### Prerequisites
- Node.js
- MongoDB or MongoDB Atlas account

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/nz-m/SocialEcho.git
Navigate to the project directory and install dependencies for both the client and server:

bash
Copy code
cd client
npm install
cd server
npm install
Create a .env file in both the client and server directories and add the environment variables as shown in the .env.example files.

Start the server:

bash
Copy code
cd server
npm start
Start the client:

bash
Copy code
cd client
npm start
Configuration
Run the admin_tool.sh script from the server directory to configure the admin account and set up initial communities:

bash
Copy code
./admin_tool.sh
.env Variables
For email service and content moderation, set the required variables in your .env file.
## My Contributions
- Developed the automated content moderation system utilizing various NLP APIs.
- Implemented context-based authentication to enhance user security.
- Created user interface components using React.js and integrated them with backend services.
- Set up the database schema and managed data interactions with MongoDB.
- Designed the admin and moderator dashboards for effective community management.

## Impact
SocialEcho aims to provide a safe and engaging environment for users to connect and share content. By leveraging automated content moderation and context-based authentication, the platform ensures compliance with community guidelines and protects user accounts from unauthorized access. The implementation of these features not only enhances user experience but also fosters a positive online community.

License
This project is licensed under the MIT License.
