# Real-Time Tracker

## 🚀 Overview
A real-time location tracking web application built using **Node.js**, **Express**, **Socket.IO**, and **Leaflet.js**. This project enables users to share their live locations dynamically, displaying them on an interactive map.

## 🌟 Features
- 🔄 **Real-Time Geolocation Tracking** using `navigator.geolocation`
- ⚡ **Instant Updates with WebSockets** via `Socket.IO`
- 🗺️ **Interactive Map Visualization** powered by `Leaflet.js` and `OpenStreetMap`
- 👥 **User Connection & Disconnection Handling**

## 📂 Project Structure
```
Real-Time-Tracker/
│── public/           # Static files (CSS, client-side JS)
│── views/            # EJS templates for rendering HTML
│── app.js            # Main server file
│── package.json      # Project dependencies
│── steps.yaml        # Deployment or process steps (optional)
```

## 🔧 Installation & Setup
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Anjali-Kumari20-dot/Real-Time-Tracker.git
```
### 2️⃣ Navigate to the Project Directory
```bash
cd Real-Time-Tracker
```
### 3️⃣ Install Dependencies
```bash
npm install
```
### 4️⃣ Start the Server
```bash
node app.js
```
or with **nodemon**:
```bash
nodemon app.js
```
### 5️⃣ Open the Application
- Visit:
  ```
  http://localhost:3000
  ```

## 🏗️ How It Works
### Backend (Node.js & Express)
1. Initializes a **Socket.IO server** to handle real-time events.
2. Listens for `send-location` events and broadcasts updates to all users.
3. Manages user connections and disconnections.

### Frontend (HTML, Leaflet.js & Socket.IO)
1. Uses **navigator.geolocation** to track user locations.
2. Sends location data through **WebSockets**.
3. Displays users on a **Leaflet.js** map.
4. Removes disconnected users from the map.

## 🛠️ Technologies Used
- **Node.js**
- **Express.js**
- **Socket.IO**
- **Leaflet.js**
- **EJS**
- **OpenStreetMap**
- **HTML/CSS/JavaScript**

## 📌 Future Enhancements
✔️ Add user authentication  
✔️ Store historical location data  
✔️ Integrate Google Maps API  
✔️ Display user details dynamically  

## 📜 License
This project is licensed under the [MIT License](LICENSE).

