# 🛡️ SafePath — Intelligent Route Safety & Travel Assistance Platform

SafePath is a full-stack web application that helps users plan **safe travel routes**
by combining real-time routing, geospatial mapping, and risk analysis.

The platform visualizes routes on an interactive map, evaluates **route safety scores**,
and is designed to progressively integrate **weather and disaster intelligence**.

---

## 🚀 Key Features

- 🔐 Authentication & protected dashboard
- 🗺️ Interactive route planning using OpenRouteService (ORS)
- 🧠 Route safety scoring (SAFE / CAUTION / DANGER)
- 🎨 Color-coded route segments on map
- 📍 Auto-zoom map to route bounds
- ⚙️ Modern Next.js App Router architecture

---

## 🧩 Tech Stack

**Frontend**
- Next.js (App Router)
- React
- Tailwind CSS
- Leaflet / React-Leaflet

**Backend**
- Next.js API Routes
- OpenRouteService API

**Tools**
- TypeScript
- ESLint
- Git & GitHub

## 🛠️ Local Setup

### Prerequisites

- Node.js 20 or later
- npm

### Run the application

1. Clone this repository and open the project directory.
2. Install the dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

The project also provides `npm run build` to create a production build and `npm start` to serve that build locally.

---

## 📌 Project Status

- ✅ Phase 1: Authentication & Dashboard
- ✅ Phase 2: Route Planning & Safety Visualization
- 🔄 Phase 3: Weather & Disaster Intelligence (in progress)

---

## 👨‍💻 Purpose

This project was built as a **placement-ready full-stack application**
to demonstrate real-world API integration, geospatial data handling,
and clean scalable architecture.

---

## 🔮 Future Enhancements

- 🌦️ Weather-based route risk analysis
- 🚨 Disaster alerts along routes
- 🤖 Floating AI chatbot assistant
- 📊 Admin & analytics dashboard
