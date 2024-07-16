# Sky Cast

This is a simple Flutter-based Weather App that provides current weather information and a 5-hour forecast for a specified location. The app fetches weather data from the OpenWeather API and displays it in a user-friendly interface.

## Features

- **Current Weather**: Displays the current temperature, sky conditions, pressure, humidity, and wind speed.
- **Hourly Forecast**: Provides a 5-hour weather forecast with temperature and sky conditions.
- **Refresh Functionality**: Allows users to refresh the weather data.

## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

- [Flutter](https://flutter.dev/docs/get-started/install)
- An IDE (e.g., [Android Studio](https://developer.android.com/studio) or [Visual Studio Code](https://code.visualstudio.com/))

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/yourusername/weather_app.git
   cd weather_app

2. Install Flutter dependencies:

   ```sh
   flutter pub get
   ```

3. Open the project in your preferred IDE.

4. Run the app:

   ```sh
   flutter run
   ```

### Configuration

Get your OpenWeather API key from [OpenWeather](https://openweathermap.org/api).

Create a `secrets.dart` file in the `lib` directory:

```dart
const String openWeatherAPIKey = 'YOUR_API_KEY';
```

Replace `'YOUR_API_KEY'` with your actual OpenWeather API key.

## Usage

- **Refresh Weather Data**: Press the refresh icon in the app bar to fetch the latest weather data.
- **View Hourly Forecast**: Scroll horizontally in the hourly forecast section to see the next 5 hours of weather data.

## Project Structure

```
lib
├── additional_info_item.dart      // Widget for displaying additional weather information
├── hourly_forecast_item.dart      // Widget for displaying hourly weather forecast items
├── main.dart                       // Main entry point of the app
├── secrets.dart                    // File to store the OpenWeather API key
└── weather_screen.dart             // Screen that displays the weather information
```

## Built With

- **Flutter**: The UI toolkit for building natively compiled applications for mobile, web, and desktop from a single codebase.
- **OpenWeather API**: The API used to fetch weather data.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## Acknowledgments

- OpenWeather for providing the weather data.
- Flutter for the amazing framework.
