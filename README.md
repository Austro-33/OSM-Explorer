# 🗺️ OSM Explorer

A small WebGIS project developed during the **GIS Field Practice** module at the **Berliner Hochschule für Technik (BHT)**.

The application allows users to click anywhere on an interactive OpenStreetMap map and automatically search for nearby restaurants within a **500-meter radius** using the **Overpass API**.

---

## 📸 Screenshots

### Start Page

<img width="2491" height="1235" alt="image" src="https://github.com/user-attachments/assets/f3a2dbe1-c6a9-4038-92aa-494cd0052562" />

### Restaurant Search

<img width="2467" height="1142" alt="image" src="https://github.com/user-attachments/assets/61a76d1c-1250-49fc-bd9d-299ac6e9e1b7" />


## ✨ Features

- 🗺️ Interactive OpenStreetMap map using Leaflet
- 📍 Select any location by clicking on the map
- 🍽️ Search for restaurants within a 500-meter radius
- 🟢 Green marker indicating the selected location
- 🔵 Blue markers showing all found restaurants
- 🔴 Selected restaurant highlighted in red
- 📋 Alphabetically sorted restaurant list
- 📏 Distance calculation (meters) from the selected location
- 🔍 Click a restaurant in the list to zoom directly to it
- 💬 Popups displaying restaurant names
- ℹ️ Information panel explaining how to use the application
- ⚠️ Error handling for unavailable Overpass API requests
- 🔄 Automatic removal of outdated markers after each search

---

## 🛠️ Technologies

- HTML5
- CSS3
- JavaScript (ES6)
- Leaflet.js
- OpenStreetMap
- Overpass API

---

## 🚀 Getting Started

### Requirements

- Internet connection
- Modern web browser (Chrome, Edge or Firefox)

### Installation

1. Download or clone this repository.
2. Keep all files in the same folder.
3. Open **index.html** in your browser.

Alternatively, the project can be started using the **VS Code Live Server** extension.

---

## 📖 How to Use

1. Open the application.
2. Click anywhere on the map.
3. The application searches for restaurants within a **500-meter radius**.
4. Restaurants are displayed as blue markers.
5. The selected position is shown with a green marker.
6. The restaurant list below the map is updated automatically.
7. Click a restaurant name to zoom to its location.
8. The selected restaurant is highlighted with a red marker.

---

## 📁 Project Structure

```text
OSM-Explorer/
│
├── index.html
├── marker-icon-green.png
├── marker-icon-red.png
├── marker-shadow.png
└── README.md
```

---

## 🌍 Data Sources

- **Map:** OpenStreetMap
- **Map Library:** Leaflet.js
- **Restaurant Data:** Overpass API

---

## 🎓 Project Information

This project was created as part of the **GIS Field Practice** module at the **Berliner Hochschule für Technik (BHT)**.

The goal of the project was to develop a small interactive WebGIS application using HTML, CSS and JavaScript while working with OpenStreetMap and the Overpass API.

---

## 👤 Author

**Jonas**

GitHub: https://github.com/Austro-33

---

## 📄 License

This project was created for educational purposes.
