# Real-Time Chat Application :
Welcome to the Real-Time Chat Application! This app allows users to engage in group chats without the need for a login ID. It uses session storage for chat data, ensuring that all conversations are deleted once all participants leave the group, thereby maintaining privacy.

## Features

- Anonymous Group Chats: No need to log in—simply join a group and start 
  chatting.
- Session Storage: Chat data is stored temporarily using session storage and - is automatically deleted when the group session ends.
- Privacy First: No database storage, ensuring that your conversations 
   remain - private and are not saved permanently.
- Easy to Use: Intuitive user interface, allowing users to join and leave 
  group chats seamlessly.

 ## How It Works
-Join a Chat Group: Users can join existing chat groups or create new ones 
 based on their interests.
- Real-Time Messaging: Messages are sent and received instantly within the 
 group using Socket.io.
- Session-Based Storage: The chat history is stored in the session and is 
 deleted once all participants leave, ensuring no data is saved permanently.

 ## Installation and Setup
 ### Clone the repository:
 - git clone https://github.com/nagarayu/Realtime-Chat-Application.git

 ### Navigate to the project directory:
 - cd Realtime-Chat-Application
 
 ### Install the necessary dependencies:
 - npm install

### Start the server:
  - node server.js

## Usage

- Create or Join a Group: Start a new chat session by entering a group name 
   or join an existing one.
- Chat Anonymously: Engage in conversations without needing to sign up or 
  provide any personal information.
- Leave Group: Simply close the tab or leave the group; your messages will 
  be erased from the session storage.

