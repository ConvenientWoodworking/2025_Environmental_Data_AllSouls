# 2025 Environmental Data - All Souls Cathedral

This repository contains scripts and data for analyzing temperature and humidity measurements collected by the All Souls sensors in 2025.

The main Streamlit application is `streamlit_app.py`. It loads measurement exports from the `data/` directory and provides interactive visualizations and summary statistics.

The interface now includes a **Sensor Locations** tab which displays images describing where each sensor is installed. Add your own images to the `sensor_images/` directory to populate this view.

Run the application with:

```bash
streamlit run streamlit_app.py
```
