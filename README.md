# AKAS Weather Forecast Application

## Overview
The AKAS Weather Forecast Application is a web-based tool that provides weather forecasts for cities around the world. The application fetches data from the OpenWeatherMap and Google Places APIs to display current weather conditions, temperature, and wind speed for a given city. Additionally, it fetches and displays a relevant image of the city using Google Places API.

## Features
- **City Weather Information**: Displays weather conditions, temperature, and wind speed.
- **City Details**: Provides geographical details like latitude, longitude, and country.
- **City Image**: Displays an image related to the searched city.

## Technologies Used
- HTML5
- CSS3
- JavaScript (ES6)
- jQuery
- Google Places API
- OpenWeatherMap API

## Prerequisites
- Web browser with the "Allow CORS: Access-Control-Allow-Origin" extension installed and enabled. This is required to bypass CORS policy restrictions.

## Installation
1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **Set up the CORS extension**:
   - Download and install the "Allow CORS: Access-Control-Allow-Origin" extension from the [Chrome Web Store](https://chrome.google.com/webstore/detail/allow-cors-access-control/lhobafahddgcelffkeicbaginigeejlf?hl=en).

3. **Configure API Keys**:
   - Obtain API keys from [OpenWeatherMap](https://home.openweathermap.org/users/sign_up) and [Google Cloud Platform](https://console.cloud.google.com/).
   - Replace the placeholder text in the script tags with your API keys.

## Usage
1. Open the `index.html` file in your web browser.
2. Enter the name of a city in the input field and click the "Submit" button.
3. The application will display:
   - Current weather conditions.
   - Temperature in Celsius.
   - Wind speed in knots.
   - City details including latitude, longitude, and country.
   - An image related to the city.

## File Structure
```
.
├── index.html
├── akas.css
├── images
│   ├── logo.png
│   ├── example_img.jpeg
│   ├── cloudy.png
│   ├── hot.png
│   └── anemometer.png
└── README.md
```

## Code Explanation
### HTML
- The HTML file includes sections for inputting the city name, displaying city details, and showing weather information.

### CSS
- The CSS file (`akas.css`) contains styling for the layout and presentation of the application.

### JavaScript
- The script fetches weather data using the OpenWeatherMap API and city images using the Google Places API.
- It utilizes XMLHttpRequest to handle API calls and updates the DOM with the received data.

## Notes
- Ensure that the CORS extension is enabled when using the application.
- The application currently requires manual insertion of API keys within the script tags in the HTML file.

## Troubleshooting
- **API Key Errors**: Ensure the API keys are correctly placed and valid.
- **CORS Issues**: Make sure the "Allow CORS: Access-Control-Allow-Origin" extension is installed and enabled.
- **Image Loading Issues**: Check the Google Places API configuration for any restrictions that might prevent image loading.

## Contact
For any issues or questions, please contact leu.chankunvath123@gmail.com.
