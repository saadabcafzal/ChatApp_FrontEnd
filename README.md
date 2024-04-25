# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
# Chat App Features

## Main Features to add in the Chat App

### User Authentication
- **Users can register/log in with a username**

### User Search
- **Users can search for a user**

### Friend Requests
- **Users can send a friend request to other users**
- **The user will be notified about the request**
- **Users can accept the friend request**

### Chat Functionality
- **Users can see the Chat list**
- **Users can send messages or attachments in Chat**

### Group Chats
- **Users can create a Group Chat with a minimum of 3 members and a maximum of 100 members**
- **Group admin can rename the Group, add members, or remove members**
- **The group admin can delete the group**
- **Group members can leave the group**
- **If the Group admin leaves the group then a new Admin will be assigned**

### User Management
- **Users can delete a chat / unfriend a user**

### Admin Dashboard
- **Admin Dashboard to see users, messages, and chats (Only Accessible with a Secret key)**

## Tech Stacks Used
- **MERN (MongoDB, Express.js, React, Node.js)**
- **Socket.io**
- **MUI (Material-UI)**

## Backend Environment Variables
```env
MONGO_URI=""
port=""
JWT_SECRET=""
ADMIN_SECRET_KEY=""
NODE_ENV=""
CLIENT_URL=
CLOUDINARY_CLOUD_NAME=""
CLOUDINARY_API_KEY=""
CLOUDINARY_API_SECRET=""

## Backend Environment Variables
```env
VITE_SERVER=""


