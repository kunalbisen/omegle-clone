# Omegle Clone  

## Technology Stack & Tools  
- **Node.js** (Backend Framework)  
- **Express.js** (Server Handling)  
- **Socket.io** (Real-Time Communication)  
- **EJS** (Templating Engine)  
- **Tailwind CSS** (UI Framework)  

## Features  
- ✅ **Anonymous Video Chat** – Connect with random users instantly.  
- ✅ **Real-Time Communication** – Powered by **Socket.io** for smooth, low-latency streaming.  
- ✅ **Responsive UI** – Built with **Tailwind CSS** for a modern, mobile-friendly experience.  
- ✅ **Secure Sessions** – Ensures privacy in chat connections.  

## Requirements For Initial Setup  
- Install [Node.js](https://nodejs.org/)  

## Setting Up  

### 1. Clone/Download the Repository  
```bash
git clone https://github.com/YOUR_USERNAME/omegle-clone.git
cd omegle-clone
```
### 2. Install Dependencies
```bash
npm install
```
### 3. Run the Server
```bash
npm start
```
### 4. Your app will be running at http://localhost:3000

## How It Works
1. Users visit the website and get paired with a random stranger.
2. The app uses WebSockets (Socket.io) to establish a peer-to-peer video chat connection.
3. If a user disconnects, the system will search for a new match.
4. Built-in moderation and security measures ensure safe interactions.

## Project Structure
```bash
/omegle-clone
│── /public       # Static assets (CSS, JS)
│── /views        # EJS templates
│── /routes       # Express routes
│── /socket       # WebSocket logic
│── app.js        # Main server file
│── package.json  # Dependencies & scripts

