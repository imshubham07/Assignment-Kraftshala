# Weather App

## Description

This Weather App is a React application built using Vite that allows users to search for the weather conditions of any city worldwide. The application fetches data from the OpenWeather API to display current weather information, including temperature, humidity, and weather conditions. Additionally, the app shows the current time and date of the searched city.

## Live Demo

You can view a live demo of the application [here](https://kraftshala-frontend-intern-shubham-kumar-dubey.vercel.app).

## Features

- **City Search**: Users can search for the weather of any city globally.
- **Current Weather**: Displays current temperature, humidity, and weather conditions.
- **Current Time and Date**: Shows the current time and date of the searched city.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/imshubham07/Assignment-Kraftshala.git
    cd Assignment-Kraftshala
    ```

2. **Install dependencies**:

    ```bash
    npm install
    ```

3. **Run the application**:

    ```bash
    npm run dev
    ```

    The application will be available at `http://localhost:3000`.

## Usage

1. Open the application.
2. Enter the name of the city you want to search for in the input field.
3. Click the search button or press Enter.
4. View the weather information and current time and date of the searched city.

## Technologies Used

- **React**: JavaScript library for building user interfaces.
- **Vite**: Frontend build tool that provides a faster and leaner development experience.
- **OpenWeather API**: Provides weather data.
- **CSS**: For styling the application.

## Approach

The application follows a component-based architecture, leveraging React's state and effect hooks to manage data fetching and user interactions. The primary components include a search bar for city input, a display area for weather information, and a clock component for showing the current time and date. The use of Vite ensures a fast development server and optimized builds.

## Known Issues and Limitations

- **API Rate Limiting**: The free tier of the OpenWeather API has a limit on the number of requests per minute. High usage might result in rate limiting.
- **City Name Ambiguity**: Searching for cities with common names might return weather data for unexpected locations.
- **Limited Error Handling**: The current implementation has basic error handling for network requests and user input. Improvements can be made for a better user experience.


## Acknowledgements

- [OpenWeather API](https://openweathermap.org/api) for providing the weather data.
- [Vite](https://vitejs.dev/) for the build tool.
- [React](https://reactjs.org/) for the JavaScript library.

---

