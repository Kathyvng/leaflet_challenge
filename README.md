# leaflet_challenge
# USGS Earthquake Data Visualization

## Background
The United States Geological Survey (USGS) is responsible for providing scientific data about natural hazards, ecosystems, environmental health, and the impacts of climate and land-use change. Their scientists develop methods and tools to supply timely and relevant information about the Earth and its processes.

To better educate the public and government organizations, the USGS needs tools to visualize their earthquake data. This project aims to develop a meaningful visualization that highlights earthquake data, helping USGS to communicate the importance of understanding and addressing natural hazards.

---

## Project Overview
This project visualizes USGS earthquake data using Leaflet.js. The map shows earthquake locations, magnitudes, and depths. Markers on the map vary in size and color to reflect the magnitude and depth of the earthquakes, providing an intuitive way to understand the dataset.

---

## Deliverables
- **Interactive Earthquake Map**
- Visualization includes:
  - Earthquake markers sized by magnitude.
  - Marker colors representing earthquake depth.
  - Popups displaying additional earthquake details.
  - A legend for depth-based color coding.

---

## Installation & Usage
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the `Leaflet_Part_1` directory:
   ```bash
   cd Leaflet_Part_1
   ```

3. Ensure the following directory structure:
   ```
   Leaflet_Part_1/
   ├── index.html
   ├── static/
   │   ├── css/
   │   │   └── style.css
   │   └── js/
   │       └── logic.js
   ├── images/
   ```

4. Run the project using a Live Server:
   - Open `index.html` with a Live Server extension (e.g., Live Server in VS Code).

5. View the interactive earthquake map in your browser.

---

## Instructions
### Part 1: Create the Earthquake Visualization

1. **Fetch Data:**
   - Visit the [USGS GeoJSON Feed](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) to get the earthquake dataset.
   - Use the "All Earthquakes from the Past 7 Days" dataset.

2. **Map Setup:**
   - Use Leaflet to create an interactive map centered at an appropriate location.

3. **Visualize Earthquake Data:**
   - Plot earthquake markers based on latitude and longitude.
   - Scale marker size by magnitude.
   - Color markers based on depth.

4. **Add Features:**
   - Popups with earthquake magnitude, depth, and location.
   - A legend explaining the color scheme for depth.

---

## Files
- `index.html`: Main HTML file for rendering the map.
- `static/css/style.css`: CSS file for styling.
- `static/js/logic.js`: JavaScript file containing the map logic.
- `images/`: Folder for screenshots or related images.

---

## Resources
- [Leaflet.js Documentation](https://leafletjs.com/)
- [USGS GeoJSON Feed](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php)

---

## License
This project is licensed under the MIT License. See `LICENSE` for more details.

---

## Acknowledgments
- USGS for providing earthquake data.
- Leaflet.js for the interactive map library.

## Code Source: Xpert learning Assistant
https://bootcampspot.instructure.com/courses/6252/external_tools/313
