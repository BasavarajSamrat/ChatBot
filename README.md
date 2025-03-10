ChatBot

A real-time chatbot application built with Spring Boot WebSocket for localhost communication.

🚀 Features

Real-time messaging using WebSockets

Simple UI with Bootstrap

Supports multiple users

Works on localhost

📦 Project Structure

.
├── src/                         # Java source code
│   ├── main/
│   │   ├── java/com/example/chatbot/   # Backend Java files
│   │   ├── resources/           # Static files and configuration
│   │   │   ├── application.properties
│   │   │   ├── static/          # Frontend HTML, CSS, JS
│   │   │   ├── templates/       # Thymeleaf templates (if used)
├── pom.xml                      # Maven dependencies
├── README.md                    # Project documentation
└── ...

⚙️ Installation & Setup

1️⃣ Clone the Repository

git clone https://github.com/BasavarajSamrat/ChatBot.git
cd ChatBot

2️⃣ Install Dependencies

Ensure you have Java 17+ and Maven installed. Then, run:

mvn clean install

3️⃣ Run the Application

mvn spring-boot:run

The server will start at http://localhost:8080

4️⃣ Open the Chat

Open a browser and go to:http://localhost:8080/chat

🔌 WebSocket Endpoints

Endpoint

Description

/chat

WebSocket handshake

/topic/message

Broadcasts messages

/app/sendMessage

Sends a message

🛠 Technologies Used

Spring Boot (WebSockets, STOMP)

SockJS & STOMP.js (WebSocket communication)

Bootstrap 5 (Frontend UI)
