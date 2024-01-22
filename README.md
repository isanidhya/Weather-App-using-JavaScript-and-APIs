### Weather App

This Weather App is a simple web application that allows users to retrieve real-time weather data for a specified city using the OpenWeatherMap API.

#### Tech Stack:

- **JavaScript:** Used for the frontend logic.
- **OpenWeatherMap API:** Utilized as a RESTful API for fetching weather data.

#### Project Structure:

```plaintext
weather-app/
|-- index.html
|-- style.css
|-- script.js
|-- README.md
```

#### Getting Started:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/weather-app.git
   cd weather-app
   ```

2. **Obtain an OpenWeatherMap API Key:**

   - Sign up on the [OpenWeatherMap website](https://openweathermap.org/api) to obtain your API key.
   - Replace `YOUR_OPENWEATHERMAP_API_KEY` in `script.js` with your actual API key.

3. **Run the Application:**

   - Open the `index.html` file in a web browser.

#### Application Features:

- Users can input a city or location to get current weather conditions.
- JavaScript makes asynchronous API calls to fetch weather data from the OpenWeatherMap API.
- Retrieved data is displayed in a user-friendly format on the webpage.
- Error handling is implemented for cases where the location is not found or the API call fails.

#### Project Author:

[Sanidhya Sahu](https://linkedin.com/in/sanidhya-sahu/)

#### Acknowledgments:

- [OpenWeatherMap API](https://openweathermap.org/api)
