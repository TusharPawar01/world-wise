# 🌍 WorldWise

A travel-tracking web app. Click anywhere on a world map to save the cities you have visited, add the date and notes about your trip, and see all your adventures in one place.

## 🔗 Live Demo

**[https://world-wise-l8n9.onrender.com](https://world-wise-l8n9.onrender.com)**

> Hosted on Render's free plan, so the first load may take a few seconds.

**Demo login**

| Email | Password |
| --- | --- |
| jack@example.com | qwerty |

## ✨ Features

- Interactive world map (Leaflet + OpenStreetMap)
- Click on the map to pick a place and add it as a visited city
- City name, country and flag emoji are filled in automatically using reverse geocoding
- Add the visit date (date picker) and your own notes
- View all cities, or see the list of countries you have visited
- Delete cities you no longer want to keep
- "Use your position" button to centre the map on your current location
- Login system with protected routes (demo authentication)
- Pages are lazy loaded for faster performance
- Fully routed app: Home, Product, Pricing, Login and App pages

## 🛠️ Tech Stack

- **React 18** (Hooks, Context API, useReducer)
- **Vite**
- **React Router v6**
- **React Leaflet**
- **React Datepicker**
- **CSS Modules**
- **json-server** (mock REST API)
- **BigDataCloud API** (reverse geocoding)

## 📁 Project Structure

```
src/
├── components/   # Map, Form, CityList, CountryList, Sidebar, etc.
├── contexts/     # CitiesContext, FakeAuthContext
├── hooks/        # useGeolocation, useUrlPosition
├── pages/        # Homepage, Product, Pricing, Login, AppLayout
├── App.jsx
└── main.jsx
data/
└── cities.json   # mock database
```

## 🚀 Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/TusharPawar01/world-wise.git
cd world-wise

# 2. Install dependencies
npm install

# 3. Start the fake API (runs on port 9000)
npm run server

# 4. In a new terminal, start the app
npm run dev
```

Then open the local URL shown in the terminal (usually `http://localhost:5173`).

## 👨‍💻 Author

**Tushar Pawar**
GitHub: [@TusharPawar01](https://github.com/TusharPawar01)
