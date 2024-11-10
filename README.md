# space
small project on svelte, bun, sveltethree, and modern front end framework

## Overview
This project is a 3D interactive web application built with Svelte and Svelthree. The app lets users explore a scaled model of space, navigate between celestial bodies, and view detailed information about stars and planets. The goal is to create an immersive and educational experience using real ephemeris data.

## Features
### Initial Scope

#### 3D Space Environment:
A scalable 3D space environment where users can traverse and explore different celestial bodies.
Basic celestial objects such as stars, planets, and moons represented as 3D models.

#### User Navigation:
Allow users to freely navigate the space using standard controls (e.g., pan, zoom, rotate).
Camera controls to ensure smooth user movement between objects.

#### Interactive Objects:
Each celestial body can be clicked or hovered over to display basic information.
Information panel shows details like the name, type, distance from Earth, and other relevant data.

#### Real-time Data Fetching:
Integration with an ephemeris API to fetch and display accurate data.
Display relevant data (e.g., current position, distance, orbital path) based on ephemeris data.

### Technology Stack
- Frontend Framework: Svelte
- 3D Graphics Library: Three.js (via Svelthree)
- Data API: Ephemeris API for real-time data
- Bundler: Bun
