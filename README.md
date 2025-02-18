# 🚀 Chatty App

**Chatty App** is a full-stack real-time chat application built using the MERN stack with Socket.io, TailwindCSS, and Daisy UI. It features authentication, authorization, real-time messaging, online user status, and state management with Zustand.

You can check out the app [here](https://chatty-app-c2xo.onrender.com/).

![Screenshot 2025-02-18 234602](https://github.com/user-attachments/assets/ac02bdb7-c867-4fb3-9608-8f69be573783)
![Screenshot 2025-02-18 234807](https://github.com/user-attachments/assets/fc4d1a28-12b0-491b-8733-edfbc7601f6e)
![Screenshot 2025-02-18 235333](https://github.com/user-attachments/assets/f1dd19d9-bf6a-4d6f-9f4b-58c8c4b3c68c)

## ✨ **Features**
- 🔐 Authentication & Authorization using JWT
- 💬 Real-time messaging with Socket.io
- 🟢 Online user status
- 🌐 Global state management with Zustand
- ☁️ Image upload with Cloudinary
- 🎨 Styled using TailwindCSS & Daisy UI
- 🛠️ Error handling on both client and server
- 🚀 Easy deployment setup


## ⚙️ **Tech Stack**
- **Frontend:** React, Zustand, TailwindCSS, Daisy UI  
- **Backend:** Node.js, Express.js, Socket.io  
- **Database:** MongoDB  
- **Image Hosting:** Cloudinary  
- **Authentication:** JWT  


## 🔧 **Setup & Installation**

1. **Clone the repository:**
    ```bash
    git clone https://github.com/akansh30/chatty_app.git
     cd chatty-app
    ```

2. **Install dependencies:**
    ```bash
    npm install
    ```

3. **Create a `.env` file in the root directory and add:**
    ```env
    MONGODB_URI=YOUR_MONGODB_URI
    PORT=5001
    JWT_SECRET=YOUR_JWT_SECRET

    CLOUDINARY_CLOUD_NAME=YOUR_CLOUD_NAME
    CLOUDINARY_API_KEY=YOUR_API_KEY
    CLOUDINARY_API_SECRET=YOUR_API_SECRET

    NODE_ENV=development
    ```

4. **Build the app:**
    ```bash
    npm run build
    ```

5. **Start the app:**
    ```bash
    npm start
    ```
