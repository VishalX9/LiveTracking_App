<img width="2554" height="1538" alt="image" src="https://github.com/user-attachments/assets/ebbd38e2-062c-49c1-9341-c201352028b1" /># Live-Tracking-App 📌


<img width="1277" height="769" alt="Screenshot 2026-06-26 at 10 35 30 AM" src="https://github.com/user-attachments/assets/255e42e6-66b2-413e-8e5e-6a86421befbb" />

## Overview

This project is a real-time device tracking application that utilizes geolocation and WebSockets to monitor device locations and display them on a map. Built with Node.js, Express, Socket.io, and Leaflet.js, it enables seamless real-time updates and dynamic map rendering.

## Features

1. Live Device Tracking: Continuously monitors and updates device locations in real-time.
2. Interactive Map with Markers: Displays device locations on a dynamic map with easily identifiable markers.
3. Automatic Marker Updates: Instantly updates markers as device locations change.
4. Multi-Device Support: Tracks and displays multiple devices simultaneously.

## Tech used

-**Node.js**

-**Express.js**

-**Socket.io**

-**Leaflet.js**

-**EJS (Embedded JavaScript templating)**

## Structure

![image](https://github.com/user-attachments/assets/c4c791df-a90d-48d3-aa66-228e4ed02e2f)

## Working of the Live Device Tracking Application 🗺️

## Backend

1. Server Initialization: The server is set up using Express.js, which initializes an HTTP server to handle client requests.
2. Socket.io Integration: Socket.io is implemented for real-time communication. When a client connects, a unique socket ID is assigned.
3. Geolocation Data Handling: The server listens for geolocation updates from connected clients. Upon receiving data, it broadcasts location updates to all clients in real time.
4. Client Disconnection Management: If a client disconnects, the server removes the associated data and notifies other clients to delete the corresponding marker from the map.
   
## Frontend

1. Geolocation Retrieval: The browser’s Geolocation API continuously tracks the device’s position.
2. Socket.io Client: The client establishes a WebSocket connection with the server using Socket.io for real-time updates.
3. Location Transmission: The client sends its current geolocation to the server at regular intervals.
4. Map Rendering: An interactive map is generated using Leaflet.js, with markers representing device locations.
5. Live Updates: As new location data is received, marker positions on the map update dynamically.
6. Marker Management: The client-side logic efficiently handles creating, updating, and removing markers based on real-time server data.
   
## Conclusion

The **Live-Tracking-App** demonstrates how modern web technologies can be combined to build a fast, responsive, and scalable real-time location tracking system. By leveraging **Express.js** for the backend, **Socket.io** for instant bidirectional communication, the **Geolocation API** for live location updates, and **Leaflet.js** for interactive map visualization, the application provides a seamless tracking experience for multiple connected devices.

This project serves as a strong foundation for real-world applications such as fleet management, delivery tracking, employee monitoring, and location-sharing services. Its modular architecture also makes it easy to extend with features like user authentication, route history, geofencing, notifications, and persistent location storage.

📍 **Real-Time Tracking** • 🌍 **Interactive Maps** • ⚡ **Instant Updates** • 📱 **Multi-Device Support**



