# 🌍 AIR ATLAS — Interactive Air Quality Explorer

### Know the Air. Read the Patterns.

**AIR ATLAS** is an interactive air-quality exploration and visual analytics platform designed to make environmental data easier to understand, explore, and interpret.

The platform brings together historical AQI records, hourly pollutant measurements, monitoring station information, and geographical visualizations to uncover pollution patterns across North India.

Rather than presenting pollution statistics as isolated numbers, AIR ATLAS transforms environmental datasets into an interactive analytical experience.

---

## ✨ Key Features

### 1. Interactive Dataset Explorer
- Explore three connected environmental datasets.
- Search datasets using an integrated search bar.
- Sort datasets alphabetically.
- Interactive cards with 3D hover effects.
- Animated information panels containing dataset insights, limitations, and recommended analytical workflows.

### 2. Interactive Geographical Map
- Interactive North India map powered by Leaflet.js.
- OpenStreetMap integration.
- 33 city-level reference markers.
- Marker clustering for better geographical exploration.
- Hover over markers to preview air-quality information.
- Click markers to access detailed PM2.5 readings.
- Interactive zooming and panning.

### 3. Visual Analytics Dashboard

The platform includes seven analytical visualizations covering different aspects of air quality.

These visualizations explore:

- City-level PM2.5 rankings.
- Monthly pollution trends.
- Hourly PM2.5 variations.
- Pollutant and weather correlations.
- Data completeness analysis.
- Station-level PM2.5 rankings.
- Geographical distribution of pollution.

Charts can be expanded using an interactive lightbox interface.

### 4. Data Quality & Reliability Analysis

AIR ATLAS highlights important data-quality challenges instead of presenting incomplete information as reliable evidence.

Key findings from the supplied dataset analysis:

| Metric | Observation |
|---|---:|
| Hourly records (2025) | 414,255 |
| Monitoring stations | 48 |
| Cities covered | 35 |
| Missing PM2.5 readings | 47.2% |
| Historical coverage | 2017–2023 |
| Unique historical Station IDs | 31 |
| Combined station identities | 78 |

The platform also highlights:
- Missing pollutant observations.
- Inconsistent historical station identifiers.
- Geographic coordinate limitations.
- Coverage-based filtering for reliable comparisons.

---

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| HTML5 | Website structure |
| CSS3 | Styling, animations and responsive layouts |
| JavaScript | Interactive functionality |
| Leaflet.js | Interactive geographical mapping |
| OpenStreetMap | Map tile provider |
| jQuery | JavaScript utility library |
| Leaflet MarkerCluster | Geographical marker clustering |

---

## 📊 Datasets

AIR ATLAS is built around three primary environmental data collections.

**1. Air Quality Hourly (2025)**

Contains hourly air-quality observations across North India. The analysis focuses on pollutant availability, PM2.5 coverage, temporal patterns, and geographical differences.

**2. AQI History (2017–2023)**

Historical AQI records used to examine long-term pollution patterns and investigate inconsistencies in monitoring station identities.

**3. Monitoring Stations**

A station registry containing State, Station ID, City, and Station Name. The registry provides administrative information but does not include geographic coordinates.

---

## ⚙️ Getting Started

AIR ATLAS is a standalone HTML-based application.

### Prerequisites
- A modern web browser.
- Internet connection for loading OpenStreetMap tiles and external libraries.

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/YOUR-USERNAME/AIR-ATLAS.git
```

**2. Navigate to the project directory**

```bash
cd AIR-ATLAS
```

**3. Open the application**

Open `AIR_ATLAS_Visual_Analytics.html` in your browser.

Alternatively, use the VS Code Live Server extension.

---

## 📁 Project Structure

```text
AIR-ATLAS/
│
├── AIR_ATLAS_Visual_Analytics.html
│
└── README.md
```

The HTML file contains the page structure, styling, interactive scripts, map integration, and embedded visualization assets.

---

## ⚠️ Data Limitations

Environmental data must be interpreted carefully.

- Missing PM2.5 readings do not indicate clean air.
- City-level map markers represent approximate city centres, not exact monitoring station coordinates.
- Historical station IDs may represent multiple station identities.
- City and station rankings use a minimum PM2.5 data-coverage threshold of 70%.
- Correlation between pollutants and weather variables does not establish causation.
- Map tiles require an active internet connection.

These limitations are documented to encourage transparent and responsible interpretation of environmental data.

---

## 🎯 Project Objective

The primary objective of AIR ATLAS is to make environmental data more accessible through interactive geographical exploration and evidence-based visual analytics.

By combining data exploration, spatial representation, and analytical insights, the platform demonstrates how environmental datasets can be transformed into meaningful information for researchers, students, and environmental analysts.

---

## 🚀 Future Scope

Potential improvements include:

- Integration of real-time AQI data feeds.
- Station-level geographical mapping using verified coordinates.
- Predictive air-quality analysis using machine learning.
- Pollution hotspot detection.
- Advanced geographical heatmaps.
- Automated data-quality monitoring.
- Backend integration for dynamic dataset updates.

---

## 👨‍💻 Project Information

**Project:** AIR ATLAS — Interactive Air Quality Explorer  
**Domain:** Environmental Data Science & Visual Analytics  
**Focus:** Air Quality Monitoring, Geospatial Analysis & Data Visualization

---

*Observe carefully. Interpret honestly.*

**AIR ATLAS — Know the Air. Read the Patterns.**
