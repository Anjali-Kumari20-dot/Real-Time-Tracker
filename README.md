Real-Time Tracker
Overview
A real-time location tracking application using Node.js, Express, Socket.IO, and Leaflet.js. This project enables users to share their live locations dynamically, displaying them on an interactive map.

Features
Live geolocation tracking using navigator.geolocation

Real-time communication using Socket.IO

Map visualization with Leaflet.js and OpenStreetMap

User connection and disconnection handling

Installation & Setup
1️⃣ Clone the Repository
bash
git clone https://github.com/Anjali-Kumari20-dot/Real-Time-Tracker.git
2️⃣ Navigate to the Project Directory
bash
cd Real-Time-Tracker
3️⃣ Install Dependencies
bash
npm install
4️⃣ Start the Server
bash
node app.js
or if using nodemon:

bash
nodemon app.js
5️⃣ Open the Application
Open your browser and go to: http://localhost:3000

Project Structure
Real-Time-Tracker/
│── public/           # Static files (CSS, client-side JS)
│── views/            # EJS templates for rendering HTML
│── app.js            # Main server file
│── package.json      # Project dependencies
│── steps.yaml        # Deployment or process steps (optional)
How It Works
Backend (Node.js & Express)
Initializes a Socket.IO server to handle real-time events.

Listens for send-location events and broadcasts updates to all connected users.

Manages user connections and disconnections.

Frontend (HTML, Leaflet.js & Socket.IO)
Uses navigator.geolocation to track user locations.

Sends location data through WebSockets.

Displays users on a Leaflet.js map.

Removes disconnected users from the map.

Technologies Used
Node.js

Express.js

Socket.IO

Leaflet.js

EJS

OpenStreetMap

HTML/CSS/JavaScript

Future Enhancements
✔️ Add user authentication ✔️ Store historical location data ✔️ Integrate with Google Maps API ✔️ Display user information in a sidebar

License
This project is licensed under MIT License.
