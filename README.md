# SVG World Map Demo (Enhanced)

This project utilizes the **SVG World Map JS** library to create an interactive world map, featuring custom data display and continent-based coloring.

---

## 🌎 Live Demo

View the enhanced map running on a live web server here:

[https://starkmaps.netlify.app/](https://starkmaps.netlify.app/)

---

## 💡 Usage and Features

This map application demonstrates the following custom functionality:

1.  **Map Interaction:** Countries highlight on hover, displaying a **finger pointer** (`cursor: pointer`) to indicate interactivity.
2.  **Enhanced Tooltip:** The hover information box displays detailed country information, including:
    * **Country Name**
    * **Capital City**
    * **Continent**
    * **Official Languages**
3.  **Visual Enhancement:** Countries are initially colored based on their **Continent** (requires custom data integration in `worldmap.js`).
4.  **Data Source:** The map visualization layer is integrated with external data scraped from a Wikipedia table (`Press Freedom Index`) and combined with custom geo-details data.
5.  **Time Controls:** Includes controls for playing, pausing, and scrubbing through time-series data (currently used to display the dynamic Wikipedia data).

---

## 🛠️ Credits and Original Library

This project is built upon the foundational work of the **SVG World Map JS** library.

* **Author:** Raphael Lepuschitz
* **Source:** [https://github.com/raphaellepuschitz/SVG-World-Map](https://github.com/raphaellepuschitz/SVG-World-Map)
* **License:** MIT

---

## ⚙️ Setup Notes

Due to browser security restrictions (Same-Origin Policy), this map **must be run on a local web server** (e.g., Python's `http.server` or VS Code's Live Server extension) for the interactive features (hovering/tooltips) to function correctly. Running directly from a `file://` path will cause errors.
