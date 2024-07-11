# Chit Chats

**Chit Chats** is a real-time messaging application built using the MERN stack and socket.io. It supports both one-on-one and group messaging with various features to enhance user interaction and experience.

## Features

- **User Registration**: Register with a name, email, password, and an optional profile picture.
- **Secure Login**: Login securely using JWT for authentication and bcrypt for password hashing.
- **One-on-One Messaging**: Chat directly with other users.
- **Group Messaging**: Create and participate in group chats.
- **User Search**: Search for users by name or email address to chat with them or to add them to a group chat.
- **Chat List**: All chats are displayed on the left side of the screen. Selecting a chat opens the conversation.
- **Real-Time Messaging**: Messages are delivered in real-time using socket.io, so there's no need to refresh the application to receive new messages.
- **Typing Indicator**: Shows when the other person is typing and hides when they stop.
- **Emoji Support**: Send and receive emojis in messages.
- **Profile Viewing**: View other users' profiles.
- **Notifications**: Receive notifications for new messages when you're not in the chat, and get redirected to the chat upon clicking the notification.
- **Persistent Messages**: All messages are stored in the database and are not temporary.
- **Group Chat Settings**: Configure settings for group chats, such as changing the chat name, and adding or removing users (admin only). Users can also leave the group chat.
- **Cloud Storage**: Profile pictures are stored in Cloudinary.

## Installation

### Prerequisites

- Node.js
- MongoDB
- React.js

### Steps

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/chit-chats.git
    ```
2. Navigate to the project directory:
    ```sh
    cd chit-chats
    ```
3. Install backend dependencies:
    ```sh
    npm install
    ```
4. Navigate to the frontend directory:
    ```sh
    cd client
    ```
5. Install frontend dependencies:
    ```sh
    npm install
    ```
6. Start the development server:
    ```sh
    npm run dev
    ```
7. Open your browser and navigate to `http://localhost:3000`.
8. Configure .env file for MONGO_URI and PORT and JWT_SECRET.

## Usage

1. **Register** a new user or **login** with existing credentials.
2. **Search** for users by name or email to start a chat or create a group chat.
3. **Send messages** in real-time, with typing indicators and notifications.
4. **Manage group chats** with settings for adding/removing users and changing the chat name.

## Contributing

Contributions are welcome! Please fork this repository and submit pull requests.

## Contact

For any questions or feedback, please open an issue in this repository.

## Live Demo

Check out the live demo [here](https://chit-chats-5mtv.onrender.com).

