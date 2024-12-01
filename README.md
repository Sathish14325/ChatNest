# ChatNest  

A Full Stack Chatting App that provides real-time communication between users. This application is built with modern web technologies and ensures secure data storage and transmission.  

## Features  
- **Real-Time Communication**: Powered by **Socket.io**, enabling instant message delivery.  
- **User Authentication**: Secure login and registration with encrypted passwords.  
- **Data Storage**: User details are stored securely in an encrypted format using **MongoDB**.  
- **Responsive Design**: Works seamlessly across desktop and mobile devices.  
- **User-Friendly Interface**: Intuitive UI for a smooth chatting experience.  

## Technologies Used  
### Frontend  
- React  
- Redux (for state management)  
- CSS/Tailwind CSS/Material UI/ Chakra Ui

### Backend  
- Node.js  
- Express.js  
- Socket.io (for real-time communication)  

### Database  
- MongoDB  

### Others  
- JWT for user authentication  
- Bcrypt for password hashing  

## Installation  

### Prerequisites  
- Node.js (v14+ recommended)  
- MongoDB (local or cloud instance)  

### Steps to Run Locally  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/yourusername/chat-application.git

2. Set up environment variables:
   ```bash
   NODE_ENV=development
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret  

3. Start the development server:
  ```bash
  npm run server
  cd client  
  npm start


