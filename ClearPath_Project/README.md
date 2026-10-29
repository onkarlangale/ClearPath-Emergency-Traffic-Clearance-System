# ClearPath — Emergency Traffic Coordination Prototype

ClearPath is a student prototype demonstrating a workflow for creating and reviewing emergency vehicle coordination alerts.

## Features
- Select Ambulance, Fire Engine, or Police Vehicle
- Enter a route zone and ETA
- Optional short note
- Express backend validation through REST API
- Dashboard summary and alert history
- Responsive desktop/mobile interface

## Technology
HTML, CSS, JavaScript, Node.js, Express, REST API.

## Run locally
1. Install Node.js 18 or newer.
2. Open a terminal in this folder.
3. Run `npm install`
4. Run `npm start`
5. Open `http://localhost:10000`

## Deploy on Render
Create a public GitHub repository containing all project files. In Render, create a Web Service connected to that repository. Use `npm install` as the build command and `npm start` as the start command.

## Limitations
This is a prototype. Alerts are held in server memory and may reset when the server restarts. It does not connect to emergency services, track vehicles in real time, use live traffic data, or control traffic signals. Do not use it for real emergencies.
