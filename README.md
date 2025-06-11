# 📍 Real-Time Device Tracker

A Node.js-based web application that uses **Socket.IO**, **Leaflet.js**, and the **Geolocation API** to track user devices on a live map in real time.


## 🚀 Features

- 🔴 Real-time location sharing
- 🌍 Interactive map using Leaflet.js
- 📡 Broadcast location updates to all connected clients
- 📦 Built using Express.js, Socket.IO, EJS

---


## 🧠 Tech Stack

- **Frontend**: HTML, CSS, Leaflet.js, Socket.IO client
- **Backend**: Node.js, Express.js, Socket.IO
- **View Engine**: EJS

---


🚀 Setup Instructions
Follow these steps to run the project locally on your machine:

1️⃣ Clone the Repository
Open a terminal and run:
```bash
git clone https://github.com/jiyasangwan/Real-time-device-tracker.git
cd Real-time-device-tracker
```

2️⃣ Install Dependencies
Install all required Node.js packages using npm:
```bash
npm install
```

3️⃣ Start the Server
Start the server using Node.js:
```bash
node app.js
```

Or, if you have nodemon installed:
```bash
npx nodemon app.js
```

5️⃣ Open the App in Browser

Go to your browser and open:
```bash
http://localhost:3000
```



✅ Requirements
- Node.js (v14 or above)

- Internet access (for Leaflet maps)

- Allow location access in your browser



📱 Testing on Multiple Devices
- Connect both devices (PC & mobile) to the same Wi-Fi.

- Run ipconfig (Windows) or ifconfig (macOS/Linux).

- Find your local IP, e.g., 192.168.1.10.

- On mobile browser, open:
```bash
http://192.168.1.x:3000
```
Live preview:
![image](https://github.com/user-attachments/assets/da4cdd86-c185-4227-a14d-945e1f0cd7f3)


![image](https://github.com/user-attachments/assets/b2a5a828-bb57-41a9-8494-4c76a9903c1f)

