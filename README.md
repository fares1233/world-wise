# WorldWise

A complex single-page application (SPA) designed as a travel-tracking tool. This project focuses on integrating interactive maps, handling global state management, and synchronizing UI state with the URL.

## Live Demo
Check out the live application here: [https://loquacious-taiyaki-35b837.netlify.app/](https://loquacious-taiyaki-35b837.netlify.app/)

## Technical Highlights
* **Dynamic Routing:** Implemented sophisticated URL-based state management using React Router to synchronize the UI with location data.
* **Global State Management:** Managed complex application states using the Context API and Redux Toolkit for seamless data flow across the app.
* **Interactive Mapping:** Integrated Leaflet.js to allow users to interactively select locations and view their travel history on a global map.
* **Performance Optimization:** Utilized Vite for a fast development environment and optimized bundle sizes.
* **Form Handling and Logic:** Built custom forms to capture location-specific data and store it within a simulated backend.

## Core Functionalities
* **Location Logging:** Users can click on the map to log new cities and countries they have visited.
* **Geolocation:** Built-in support for detecting the user's current position to simplify location tagging.
* **Travel Statistics:** Real-time summary of the total number of cities and countries visited.
* **Persistent Data:** Simulated backend integration to ensure travel data is maintained throughout the session.

## Tech Stack
* **Library:** React.js.
* **Routing:** React Router.
* **State Management:** Context API, Redux Toolkit.
* **Maps:** Leaflet.js.
* **Tooling:** Vite.

## Installation and Setup
To run this project locally, follow these steps in your terminal:

```bash
# Clone the repository
git clone [https://github.com/fares1233/world-wise.git](https://github.com/fares1233/world-wise.git)

# Navigate into the project directory
cd world-wise

# Install dependencies
npm install

# Start the development server
npm run dev
npm run server
