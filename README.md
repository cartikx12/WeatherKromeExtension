# WeatherKromeExtension

## Overview

**WeatherKromeExtension** is a simple Chrome extension that provides real-time weather information based on your current location. With a clean and intuitive interface, it shows you the current temperature, weather condition, and location. This extension is built using HTML, CSS, and JavaScript, and fetches weather data from the OpenWeatherMap API.

## Features

- Displays real-time weather data based on your current location.
- Provides temperature, weather conditions, and the name of the location.
- Easy-to-use popup interface.

## Installation

To use the WeatherKromeExtension, you can either load it as an unpacked extension from your local machine or download it directly from the Chrome Web Store (if available).

### Option 1: Load as Unpacked Extension

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/WeatherKromeExtension.git
2. Open Chrome and navigate to chrome://extensions/.

3. Enable "Developer mode" by toggling the switch in the top right corner.

4. Click on "Load unpacked" and select the folder where you cloned this repository.

5. The WeatherKromeExtension icon should appear in your browser's toolbar.

### Option 2: Install from Chrome Web Store Usage 
This feature is coming soon.


## Usage
Click on the WeatherKromeExtension icon in the Chrome toolbar.

The extension will request permission to access your location.

Once permission is granted, the extension will display the current weather data for your location.

## Configuration 
To modify the API key:

1. Open the popup.js file in the scripts folder.

2. Replace the existing apiKey value with your own OpenWeatherMap API key:
const apiKey = 'your-api-key';

3. Save the changes and reload the extension in Chrome.

## Dependencies
OpenWeatherMap API: Used to fetch real-time weather data.

## Contributing 
Contributions are welcome! If you have any ideas or suggestions, feel free to submit a pull request or open an issue.

### Steps to Contribute:
1. Fork this repository.

2. Create a new branch (git checkout -b feature-branch).

3. Make your changes.

4. Commit your changes (git commit -m 'Add some feature').

5. Push to the branch (git push origin feature-branch).

6. Open a pull request.

## Support
If you encounter any issues or have any questions, feel free to open an issue in this repository.
