# GeoFence Unlocker

GeoFence Unlocker is a simple web application that uses the Google Maps JavaScript API to unlock specific content based on the user's location. The application displays a map with multiple geofenced zones. As the user enters one of the designated areas, corresponding content is automatically revealed.

## Features

- **Dynamic Geofencing:**  
  Displays two geofenced zones:
  - **Lotnisko w Chrcynnie:** A 20 km radius zone.
  - **Warszawa Nowy Świat:** A 1 km radius zone.

- **Real-Time Location Tracking:**  
  Uses the browser's Geolocation API to continuously track the user's location.

- **Visual Feedback:**  
  Marks the user's current position with a blue marker and a small blue circle.

- **Content Unlocking:**  
  Reveals specific content when the user enters one of the geofenced areas.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/sebo21cc21/Zagrywki.git
   ```

2. Open `index.html` in a browser to run the application.

## Usage

1. Allow location access when prompted by the browser.
2. Move into one of the designated geofenced zones.
3. The relevant content will automatically be displayed.

## Requirements

- A modern web browser with Geolocation API support.
- A valid Google Maps API key (replace `YOUR_API_KEY` in the script tag in `index.html`).

## Customization

- Modify the `geofenceZones` array in `index.html` to change or add geofenced locations.
- Adjust the radius values to fit specific use cases.

## License

This project is licensed under the MIT License. See `LICENSE` for more details.
