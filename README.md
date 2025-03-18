Socket Server-Client Messaging App

A simple Python-based messaging application using sockets for communication between a server and multiple clients. This project demonstrates basic network programming concepts and can be extended for cybersecurity applications.

📌 Features
✅ Supports real-time communication between server and clients.
✅ Uses TCP sockets for reliable data transmission.
✅ Allows both sending and receiving messages between server and client.
✅ Basic error handling and graceful exit on "exit" command.

🛠️ Installation & Setup

3️⃣ Run the Server
python socket.server.py
💡 The server will listen on port 9999 and wait for client connections.

3️⃣ Run the Client
Open another terminal and run the client:
python socket.client.py
💡 The client will connect to the server and allow two-way communication.

📜 Usage Instructions
1️⃣ The server starts and waits for connections.
2️⃣ A client connects and sends a message.
3️⃣ The server receives and echoes the message back.
4️⃣ Both sides can send messages continuously.
5️⃣ Type "exit" to close the connection.

💻 Example Output
🔹 Server Terminal
pgsql
Copy
Edit
Server is listening on port 9999...
Connected by ('127.0.0.1', 54321)
Client sent: Hello, Server!
Enter message: Hi, Client!
🔹 Client Terminal
Connected to the server 127.0.0.1
Enter message: Hello, Server!
Server replied: Hi, Client!

🔐 Security Considerations (Cybersecurity Relevance)
⚠ Avoid sending sensitive data in plaintext (use encryption like TLS).
⚠ Prevent buffer overflow attacks by limiting input size.
⚠ Sanitize input to prevent command injection (if implementing a reverse shell).
