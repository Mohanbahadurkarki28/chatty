
# Chatty - Real-Time Chat Application  

**Chatty** is a real-time chat application built using the MERN stack and Socket.io, enabling seamless communication between users.

## Features  
✅ Real-time messaging with Socket.io  
✅ User authentication (JWT-based)  
✅ one-on-one chats  
✅ Typing indicators and online status  
✅ Message notifications  
✅ Responsive UI  
✅ Profile update  

## Tech Stack  
- **Frontend:** React.js, Tailwind CSS, Daisy UI  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Real-Time Communication:** Socket.io  
- **Authentication:** JWT (JSON Web Tokens)  

## Installation  

1. **Clone the repository:**  
   ```sh
   git clone https://github.com/Mohanbahadurkarki28/chatty.git
   cd chatty
   ```

2. **Install dependencies:**  
   ```sh
   # For backend
   cd server
   npm install

   # For frontend
   cd ../client
   npm install
   ```

3. **Set up environment variables:**  
   - Create a `.env` file in the `server` directory and add:  
     ```
     MONGO_URI=your_mongodb_uri
     JWT_SECRET=your_secret_key
     SOCKET_PORT=your_socket_port
     ```
   - Create a `.env` file in the `client` directory and add:  
     ```
     REACT_APP_BACKEND_URL=your_backend_url
     ```

4. **Run the application:**  
   ```sh
   # Start backend
   cd server
   npm start

   # Start frontend
   cd ../client
   npm start
   ```

5. **Open the app:**  
   - Go to `http://localhost:3000` in your browser.  

## Contributing  
Feel free to contribute! Fork the repo, create a new branch, and submit a pull request.  

## License  
This project is licensed under the MIT License.  

## Contact  
📧 **[Mohan Bahadur Karki](https://github.com/Mohanbahadurkarki28)**  
