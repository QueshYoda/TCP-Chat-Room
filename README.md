# TCP Chat Room

A simple chat room application using TCP sockets in Python. This project includes a server and client implementation that allows multiple users to communicate with each other.

## Features
- Multiple clients can connect to the server
- Admin functionality with authentication
- Admin can kick or ban users
- Users receive messages from other users in real time

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/QueshYoda/tcp-chat-room.git
   cd tcp-chat-room
   ```
2. Make sure you have Python installed.
3. Run the server:
   ```sh
   python server.py
   ```
4. Run the client:
   ```sh
   python client.py
   ```

## Usage
1. Start the server using `server.py`.
2. Clients can connect by running `client.py`.
3. Each client must enter a nickname.
4. If the nickname is "admin", the client must enter the admin password.
5. Admin can:
   - Kick users using `/kick <nickname>`
   - Ban users using `/ban <nickname>`
6. Messages are broadcasted to all connected clients.

## File Structure
```
├── server.py   # Server-side implementation
├── client.py   # Client-side implementation
├── bans.txt    # Stores banned users
└── README.md   # Documentation
```

## License
This project is open-source and available under the MIT License.

---
## Author
[Baha Demirtaş](https://github.com/queshyoda)


