# 💬  Real-Time Chat Application

A real-time web-based chat application built using Java and Spring Boot, enabling multiple users to exchange messages instantly using WebSocket and STOMP.
The project demonstrates bidirectional communication, server-side message routing, and dynamic UI updates without page reloads.



## 🚀 Key Highlights

Real-time messaging between multiple connected clients
WebSocket communication using STOMP protocol
Topic-based message broadcasting with Spring Messaging
Dynamic UI updates using JavaScript (no refresh required)
Clean separation of backend messaging logic and frontend rendering



## 🧩 Tech Stack

   * Backend:
  Java,
  Spring Boot,
  Spring WebSocket,
  STOMP Protocol,
  Spring Messaging
  
 * Frontend:
Thymeleaf,
JavaScript (ES6),
SockJS,
Bootstrap,
HTML, CSS

 * Build & Tools:
Maven,
IntelliJ IDEA



## 🏗️ Application Architecture (Overview)

1. WebSocket Configuration
Defines WebSocket connection endpoints
Configures application destination prefixes
Enables a simple in-memory message broker
Supports SockJS fallback for compatibility

2. Server-Side Message Handling
Processes incoming messages using Spring Messaging annotations
Routes messages to appropriate destinations
Broadcasts messages to all subscribed clients

3. Frontend Integration
Renders UI using Thymeleaf templates
Establishes WebSocket connections using SockJS and STOMP
Sends and receives messages asynchronously
Dynamically updates the chat window in real time



## 🔄 How the Application Works

1. Client connects to the server using WebSocket
2. Client subscribes to a shared topic
3. User sends a message from the UI
4. Backend processes and broadcasts the message
5. All connected clients receive updates instantly



## ▶️ Running the Application Locally

Step 1: Clone the Repository
git clone https://github.com/varun01dev/Real-Time-Chat-Application.git

Step 2: Open in IDE
Open the project in IntelliJ IDEA (or any Java IDE).

Step 3: Run the Application
Run the Spring Boot application.

Step 4: Access in Browser
http://localhost:8080/chat


Open multiple browser tabs to simulate multiple users.


## 🎯 Learning Outcomes
 * Understanding WebSocket-based real-time communication
 * Implementing message routing and broadcasting in Spring Boot
 * Integrating backend messaging with frontend UI
 * Working with STOMP protocol and SockJS fallback

## 🔮 Possible Enhancements
 * User authentication
 * Private chat rooms
 * Message persistence
 * UI validation and improvements
