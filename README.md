# VoyagerAI — AI-Powered Trip Planner ✈️

> Plan your dream trip in seconds. VoyagerAI generates personalized travel itineraries with real-time weather, crowd-level insights, hotel picks, and budget optimization — covering **40+ destinations across 5 continents**.

---

## 🌍 Demo

<!-- Add a screenshot or live link here -->
> _Live demo / screenshot coming soon_

---

## 🧩 Problem It Solves

Planning a trip from scratch takes hours of research across multiple tabs:
- Comparing hotels, activities, and costs manually
- No awareness of weather or crowd conditions
- Generic itineraries that don't fit your budget

**VoyagerAI brings it all together in one intelligent, personalized planner.**

---

## ✨ Features

| Feature | Description |
|---|---|
| 🗺 40+ Destinations | Covers major cities across Asia, Europe, Americas, Africa & Oceania |
| ☀️ Weather Analytics | Live weather data integrated into itinerary suggestions |
| 👥 Crowd-Level Insights | Avoid tourist rush hours with real-time crowd indicators |
| 🏨 Hotel Recommendations | Curated hotel picks sorted by budget and rating |
| 🎯 Activity Planner | Day-wise activity schedule tailored to your interests |
| 💰 Budget Optimizer | Automatically adjusts recommendations to fit your budget |
| 📱 Responsive SPA | Mobile-first single-page application, works on any device |

---

## 🛠 Tech Stack

- **HTML5** — Semantic structure
- **CSS3** — Responsive, mobile-first design
- **JavaScript (Vanilla)** — Dynamic UI without frameworks
- **REST APIs** — Weather data, location data, activity feeds

---

## 📁 Project Structure

```
voyagerai/
├── index.html          # Main SPA entry point
├── css/
│   └── styles.css      # All styles (responsive)
├── js/
│   ├── app.js          # Core application logic
│   ├── planner.js      # Itinerary generation engine
│   ├── weather.js      # Weather API integration
│   └── destinations.js # Destination data & recommendations
├── assets/
│   └── images/         # Destination images
└── README.md
```

---

## ⚙️ Getting Started

### Prerequisites
- A modern browser (Chrome, Firefox, Edge)
- API keys for weather service (free tier works)

### 1. Clone the repo
```bash
git clone https://github.com/srvnkumr27/voyagerai.git
cd voyagerai
```

### 2. Add your API keys
Open `js/config.js` and add:
```javascript
const CONFIG = {
  WEATHER_API_KEY: "your_openweathermap_key",
  // Add other keys here
};
```

### 3. Open in browser
Simply open `index.html` in your browser — no build step needed!
```bash
open index.html
# or use Live Server in VS Code
```

---

## 🌐 API Keys Used

| API | Purpose | Free Tier |
|---|---|---|
| [OpenWeatherMap](https://openweathermap.org/api) | Live weather data | ✅ Yes |
| [Foursquare / Google Places](https://developers.google.com/maps) | Activity & hotel data | ✅ Yes (limited) |

---

## 🗺 Supported Destinations (Sample)

**Asia** — Tokyo, Bangkok, Bali, Singapore, Mumbai, Dubai  
**Europe** — Paris, Rome, Barcelona, Amsterdam, Prague  
**Americas** — New York, Cancun, Buenos Aires, Toronto  
**Africa** — Cairo, Cape Town, Nairobi  
**Oceania** — Sydney, Melbourne, Auckland  

_...and 25+ more!_

---

## 🗺 Roadmap

- [ ] User accounts & saved trips
- [ ] AI chatbot for trip Q&A
- [ ] Flight price comparison
- [ ] Offline mode / PWA support
- [ ] Multi-language support

---

## 🙋 Author

**M Sravan Kumar Varma**
- GitHub: [@srvnkumr27](https://github.com/srvnkumr27)
- Email: srvnkumr27@gmail.com
- LinkedIn: [M Sravan Varma](https://linkedin.com/in/m-sravan-varma)

---

## 📄 License

MIT License — free to use, fork, and improve.

---

> Built to solve my own frustration with trip planning. If you find it useful, a ⭐ on GitHub means a lot!
