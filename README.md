**<p align='center'>Visit the live website : <a href="https://weatherlens-react-weather-application.onrender.com/">🌐 [Weatherlens - Weather Application]</a></p>**

# WeatherLens - React Weather Application

WeatherLens is a modern and intuitive weather application that provides real-time weather information for any location. Built using React, it leverages the Visual Crossing Weather API to deliver accurate and detailed weather updates with a responsive and visually appealing design.

## Features

- **Real-time Weather Updates**: Retrieve and display up-to-date weather information for any user-specified location.
- **Dynamic Search**: Easily search for weather details across the globe.
- **Responsive Design**: Adapts seamlessly to various screen sizes for a consistent user experience on all devices.
- **Key Weather Metrics**: Displays essential data including:
  - Temperature (Celsius/Fahrenheit)
  - Humidity
  - Wind speed and direction
- **Error Handling**: Includes mechanisms to handle invalid input or API failures gracefully.

## Tools and Technologies

- **Frontend**: React.js
- **Styling**: Tailwind CSS
- **Build Tool**: Vite
- **API**: Visual Crossing Weather API
- **HTTP Client**: Axios

## Installation

### Prerequisites

- Node.js installed on your system

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/AmritanshTiwari2160/WeatherLens-React-Weather-Application.git
   cd WeatherLens-React-Weather-application
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory and add the following:
   ```env
   REACT_APP_WEATHER_API_KEY=your_visual_crossing_api_key
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```
   
## Workflow and Architecture

### Workflow Diagram
- **User Input** → **API Call** → **Data Processing** → **Display Weather Details**

### Architecture Overview
- Component-based structure using React for dynamic updates and state management.
- Integration with the Visual Crossing Weather API for fetching weather data.

## Development Process

1. **Setup**: Created the React environment using Vite.
2. **Styling**: Applied Tailwind CSS for a clean and modern design.
3. **API Integration**: Connected to the Visual Crossing Weather API with Axios for data retrieval.
4. **Error Handling**: Implemented error-handling mechanisms for invalid input and API failures.

## Challenges and Solutions

- **API Rate Limits**: Optimized API calls to avoid hitting rate limits.
- **Responsive Design**: Ensured compatibility across a wide range of devices through rigorous testing.
- **Data Edge Cases**: Handled unusual or missing data scenarios with comprehensive error handling.

### Results
- Provides accurate and real-time weather updates for any location.
- Offers a user-friendly interface for effortless navigation.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
