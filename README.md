# 🚴🏼‍♀️ Bikewatching in Boston

An interactive project visualizing **Bluebikes station activity and bike lanes** in Boston and Cambridge. This project leverages **Mapbox GL JS**, **D3.js**, and public datasets to track station traffic, visualize trip patterns, and interactively filter data by time.

![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![JavaScript](https://img.shields.io/badge/JavaScript-ESM-blue)
![D3.js](https://img.shields.io/badge/D3.js-7.9.0-orange)
![Mapbox](https://img.shields.io/badge/Mapbox-GL%20JS-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)

🚴🏼‍♀️ **[Try Bikewatching in Boston Live](https://dylandsouza.com/bikewatching)**

---

## 🚴🏼‍♀️ Project Overview

Bikewatching in Boston is an interactive visualization of **Bluebikes stations** and bike lane infrastructure in Boston and Cambridge. Users can explore:

* Total bike traffic per station (departures + arrivals)
* Departure vs arrival ratios
* Traffic patterns over time using a slider
* Existing bike lane networks in both cities

This allows for insights into peak usage times and station popularity.

---

## ✨ Features

### 📊 Data Exploration & Visualization

* **Interactive Map**: Boston and Cambridge with Mapbox
* **Station Circles**: Size reflects total traffic; color reflects departure/arrival balance
* **Tooltips**: Detailed trip counts on hover
* **Time Filter Slider**: Filter trips by hour of the day

### 🗺 Bike Lane Layers

* **Boston**: Existing Bike Network (2022)
* **Cambridge**: Recreation Bike Facilities
* **Visualization**: Bright green lines with opacity and width indicating network

### 🤖 Data Processing

* **Load & Process JSON**: BlueBikes stations
* **Load & Process CSV**: Trip traffic
* **Compute Metrics**: departures, arrivals, totalTraffic per station
* **Dynamic Updates**: Circles reposition on map move, zoom, resize

---

## 📊 Key Insights

* Certain stations consistently experience high traffic
* Departure-heavy vs arrival-heavy stations are clearly visible via color ratio
* Time-based filtering highlights peak usage periods
* Integration of Boston and Cambridge bike lanes provides context for trip flows

---

## 🛠️ Technical Stack

* **Map Rendering**: Mapbox GL JS v2.15.0
* **Data Visualization**: D3.js v7.9.0
* **Frontend**: HTML, CSS, JavaScript (ESM modules)
* **Data Sources**:

  * [Bluebikes Station Data](https://dsc106.com/labs/lab07/data/bluebikes-stations.json)
  * [Bluebikes Traffic Data](https://dsc106.com/labs/lab07/data/bluebikes-traffic-2024-03.csv)
  * [Boston Bike Network GeoJSON](https://bostonopendata-boston.opendata.arcgis.com/datasets/boston::existing-bike-network-2022.geojson)
  * [Cambridge Bike Facilities GeoJSON](https://raw.githubusercontent.com/cambridgegis/cambridgegis_data/main/Recreation/Bike_Facilities/RECREATION_BikeFacilities.geojson)

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

* **Bluebikes Open Data** for station and traffic datasets
* **Boston Open Data** for bike network GeoJSON
* **Cambridge GIS** for bike facilities data
* **DSC 106** at UC San Diego for detailing the guiding steps for this visualization

---

## 📞 Contact

**Dylan Dsouza** - *Creator*

- Email: [dydsouza@ucsd.edu]
- GitHub: [@dsouza-dylan](https://github.com/dsouza-dylan)
- LinkedIn: [@dsouza-dylan](https://www.linkedin.com/in/dsouza-dylan/)

---

<div align="center">

**🚴🏼‍♀️ Bikewatching in Boston**

[Star this repository](https://github.com/dsouza-dylan/bikewatching) | [Report Bug](https://github.com/dsouza-dylan/bikewatching/issues) | [Request Feature](https://github.com/dsouza-dylan/bikewatching/issues)

</div
