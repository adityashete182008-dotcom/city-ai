# prompt-wars

# CityPulse AI — Pune Smart City & Urban Intelligence Platform
> **Explore Smarter. Travel Safer. Experience More.**

CityPulse AI is a next-generation smart-city urban intelligence dashboard engineered for **Pune, Maharashtra, India**. The platform seamlessly fuses **OpenStreetMap (OSM) & Leaflet geospatial intelligence**, real-time **Open-Meteo weather telemetry**, verified **civic place data (ASI, MTDC, PMRDA, PMC)**, validated **citizen reporting workflows**, and a **zero-hallucination AI Assistant**.

---

## 🚀 Key Modules & Capabilities

1. **City Explorer & OpenStreetMap (OSM)**:
   - Interactive OpenStreetMap centered on Pune coordinates (`18.5204° N, 73.8567° E`).
   - Categorized landmark markers: *Historical Sites, Tourist Attractions, Restaurants & Cafes, Hotels & Stays, Parks & Nature, Transit Hubs*.
   - Multi-filtering by budget (*Free, Budget, Moderate, Luxury*) and real-time keyword search.
   - Verified ratings, prices, and opening hours with transparent public registry source attribution.
   - Dual viewing modes: **Split View** and **Full Map Mode** with a docked horizontal interactive places carousel, fullscreen expander (`Maximize2`), and tile layer switcher (*Street*, *Satellite*, *Dark*).
   - Place Detail Modal with an embedded interactive Leaflet mini-map and transit distance / auto & cab fare calculators from Pune Railway Station.

2. **Citizen Reporting & Municipal Safety**:
   - Validated issue reporting for *Road Damage & Potholes, Traffic Congestion, Cleanliness & Dumps, Streetlight Failures, and Footpath Obstructions*.
   - Interactive map pin selection for picking precise issue coordinates.
   - Anti-spam deduplication engine (intercepts identical categories within 300m submitted in the last 15 minutes).
   - Strict `⚠️ Unverified Community Report` safety classification ensuring citizen submissions are never presented as confirmed incidents until inspected.
   - Persistent `localStorage` storage and community upvoting.

3. **Grounded AI Copilot & Itinerary Engine**:
   - Zero-hallucination AI Assistant answering natural language queries strictly using verified Pune landmarks.
   - Automated budget itinerary planner for *Budget (< ₹500/day)*, *Moderate (₹800–₹1,500/day)*, and *Luxury (₹4,000+/day)* across half-day or full-day durations.
   - Exact inter-stop distances and calibrated Pune auto/cab fare calculations.

4. **Pune Ward Benchmark & Comparison**:
   - Side-by-side comparative analysis of 8 Pune municipal zones (*Shivajinagar, Koregaon Park, Kothrud, Hinjawadi, Viman Nagar, Old Peths, Baner, Hadapsar*).
   - Metrics include AQI, Tree Canopy %, Traffic Flow Score, Safety Index, and EV Infrastructure.

5. **Live Weather & Telemetry**:
   - Integrated with Open-Meteo API for real-time Pune weather telemetry with automatic seasonal baseline fallback.

---

## 🛠️ Technology Stack

- **Frontend**: React 19, TypeScript, Vite
- **Styling**: Tailwind CSS v3, Glassmorphism, Custom Theme Tokens
- **Maps & Geospatial**: Leaflet 1.9.4, OpenStreetMap Tiles, Esri Satellite, CartoDB Dark
- **Icons**: Lucide React
- **Telemetry**: Open-Meteo REST API

---

## 📦 Setup & Installation

```bash
# Clone the repository
git clone https://github.com/adityashete182008-dotcom/prompt-wars.git
cd prompt-wars

# Install dependencies
npm install

# Run development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

Open `http://localhost:5173/` in your browser.
