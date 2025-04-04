# 🧑‍💻 TCP Chat Application (Python)

A terminal-based multi-client chat application built using Python's socket and threading libraries. Designed for fun and learning, this project simulates real-time messaging over a local network using the TCP protocol.

---

## 🚀 Features

- 🌐 **Client-Server Communication:** Built on TCP sockets  
- 👥 **Multi-Client Support:** Handles multiple clients simultaneously using threading  
- 🧑‍💻 **Nickname Assignment:** Clients are prompted to enter a nickname on joining  
- 📡 **Message Broadcasting:** Messages are sent to all connected users in real-time  
- 🔒 **“Hacker-style” Boot Message:** Simulates a connection log sequence on client join  
- 🧠 **Custom Commands:** Easy to expand for private messages, commands, or chatbots  

---

## 📂 Project Structure


---

## 🛠️ How to Run

### ✅ Step 1: Run the Server

bash
python3 server.py



✅ Step 2: Run the Client (in another terminal or another machine on the same network)

python3 client.py
🔁 You can run multiple clients to simulate a real-time group chat.


💻 Requirements

Python 3.x
No external libraries required (uses only built-in modules)


Notes

By default, the app works over localhost. To use it on other devices within the same local network, replace '127.0.0.1' with your local IP address (e.g., 192.168.1.10) in both server.py and client.py.
Made with 💻 and ☕ by Omer Naseem Chaudhry
