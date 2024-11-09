# Weather App
# Demo Link 
https://weather-95zn03c5r-abhishek99ms-projects.vercel.app/
## Overview

The Weather App is a simple React application that provides weather information for various locations. Users can search for a city to get the current weather conditions, including temperature, humidity, wind speed, and more.

## Features

- Search for weather information by city.
- Display current weather conditions.
- Show detailed weather metrics including temperature, humidity, wind speed, and heat index.
- Responsive design for different screen sizes.

## Installation

1. Clone the repository:
   ```bash
   git clone 
   ```
2. Navigate to the project directory:
   ```bash
   cd weather-app
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```

## Usage

1. Start the development server:
   ```bash
   npm start
   ```
2. Open your browser and go to `http://localhost:3000` to see the app in action.

## Project Structure

```
project-root/
├── src/
│   ├── App.jsx
│   ├── Components/
│   │   ├── BackgroundLayout.jsx
│   │   ├── WeatherCard.jsx
│   │   └── MiniCard.jsx
|   |   └── Index.jsx
│   ├── Context/
│   │   └── Index.js
│   └── assets/
│       └── icon
│       └── images
├── public/
│   ├── index.html
│   └── ...
├── package.json
├── README.md
└── ...
```

## Components

- **BackgroundLayout**: Layout component that provides the background for the app.
- **WeatherCard**: Displays the main weather information for the searched city.
- **MiniCard**: Shows additional weather details in a compact format.
- **index**: The `index.jsx` file re-exports the default exports from `BackgroundLayout.jsx`, `MiniCard.jsx`, and `WeatherCard.jsx` to simplify importing these components elsewhere in the project.

## Context

- **useStateContext**: Custom hook to manage the global state of the application, including weather data and the selected location.

## Assets

- **icon**
- **images**

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

