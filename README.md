# Tracking Device

## Overview
A real-time location tracking system that allows users to track each other's live locations on Google Maps. The system dynamically updates the position of markers as users move, ensuring real-time tracking.

## Features
- **Real-time location updates** using Socket.io
- **Google Maps integration** for displaying live locations
- **Multi-user tracking** with dynamic map markers that move as users change location
- **Marker updates** in real-time when users move to new locations or log in from another device

## Technologies Used
- **Backend:**
  - Node.js
  - Express
  - Socket.io for real-time communication
- **Frontend:**
  - Google Maps API
  - Leaflet.js for map rendering
  - EJS for rendering dynamic content
- **Database:** None (this project uses live data via Socket.io)

## Installation

1. Clone the repository:
   ```bash
   git clone <repository_url>
