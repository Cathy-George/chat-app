# Full Stack Realtime Chat App 

*COMPANY: CODTECH IT SOLUTIONS

NAME: CATHY GEORGE

INTERN ID: CT04DM551

DOMAIN: FRONT END DEVELOPMENT

*DURATION: 4 WEEEKS

MENTOR: NEELA SANTOSH

##Project_Description
This project is a fully functional real-time chat application developed using the MERN stack—MongoDB, Express.js, React.js, and Node.js—integrated with Socket.IO to support instant messaging between users. The core goal of this application is to enable seamless one-on-one communication in a fast, secure, and responsive interface, mimicking the functionality of modern chat platforms like WhatsApp or Facebook Messenger. The front-end of the application is built with React, where components are dynamically rendered based on user interactions. Context API is used for state management, ensuring that user authentication status, chat messages, and loading states are consistently handled across the application.

On the backend, Node.js and Express.js handle RESTful API requests for user registration, login, chat creation, and message exchange. Authentication is secured using JSON Web Tokens (JWT), ensuring that user data remains protected during session management. The application also integrates MongoDB as its database, with Mongoose ODM used to structure the schema for users, chats, and messages. All messages and chat metadata are stored in MongoDB, making it easy to retrieve and persist conversations even after a session ends. Real-time features such as live message delivery, online/offline status, and typing indicators are powered by Socket.IO, which enables WebSocket communication between the client and server. This ensures that messages are pushed instantly without requiring manual page refreshes or polling.

A key highlight of this application is its modern UI/UX, built using responsive design principles so that users on desktops and mobile devices enjoy a smooth experience. Users can register or log in to the platform, set up their profiles, and start chatting with other registered users in a private one-on-one chat window. The chat interface automatically updates when new messages are received or when the other user is typing, mimicking the real-time feedback users expect in professional chat platforms. The backend includes proper error handling and user validation, making it a robust system that can scale and handle larger user loads with minimal adjustments.

This project was originally inspired by an open-source tutorial and has been restructured and customized as part of my learning journey in full-stack web development. By going through the entire development process—from backend APIs to frontend integration—I gained hands-on experience with building scalable web applications, implementing real-time systems using WebSockets, and structuring MongoDB databases effectively. This project also deepened my understanding of client-server communication and session handling in web applications. Through this, I was also exposed to real-world project organization, Git version control, and deployment preparation. Overall, this chat app stands as a strong representation of my growing skills in the MERN stack and web application development, and serves as a base for future extensions such as group chats, message notifications, file sharing, or even video calling features.

### Setup .env file

```js
MONGODB_URI=...
PORT=5001
JWT_SECRET=...

CLOUDINARY_CLOUD_NAME=...
CLOUDINARY_API_KEY=...
CLOUDINARY_API_SECRET=...

NODE_ENV=development
```

### Build the app

```shell
npm run build
```

### Start the app

```shell
npm start
```
