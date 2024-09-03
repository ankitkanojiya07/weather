# Weather Forecast Website

A simple and intuitive weather forecast website built using React.js. This application allows users to search for the current weather conditions and a 5-day forecast for any city in the world.

## Features

- Real-time weather information
- 5-day weather forecast
- Search functionality for cities worldwide
- Responsive design for all devices
- Error handling for invalid city names

## Technologies Used

- React.js
- HTML5 & CSS3
- JavaScript (ES6)
- Axios (for API requests)
- weatherApi API

## Getting Started

Follow these instructions to set up and run the project locally.

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/en/download/) (version 14.x or later)
- [npm](https://www.npmjs.com/get-npm) (comes with Node.js)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/weather-forecast-website.git
    ```

2. Navigate to the project directory:

    ```bash
    cd weather-forecast-website
    ```

3. Install the dependencies:

    ```bash
    npm install
    ```

### API Key

This project uses the [OpenWeatherMap API](https://openweathermap.org/api) to fetch weather data. You need to get a free API key from their website.

1. Sign up at [weatherApi](https://www.weatherapi.com/) to get your API key.
2. Create a `.env` file in the root directory of the project.
3. Add your API key to the `.env` file:

    ```plaintext
    REACT_APP_OPENWEATHER_API_KEY=your_api_key_here
    ```

## Usage

To start the development server, run:

```bash
npm start
