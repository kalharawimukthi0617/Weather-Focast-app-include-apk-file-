# 🌦️ Flutter Weather Forecast App

![App Banner](https://github.com/username/weather-forecast-app/raw/main/screenshots/banner.png)

A beautifully designed weather forecast application built with Flutter and BLoC pattern. Get real-time weather updates for any city or your current location with a simple, intuitive interface.

## ✨ Created by [Kalhara Wimukthi](https://github.com/kalharawimukthi)

<p align="center">
  <img src="https://img.shields.io/badge/flutter-v3.13.0-blue?logo=flutter" alt="Flutter Version">
  <img src="https://img.shields.io/badge/dart-v3.1.0-blue?logo=dart" alt="Dart Version">
  <img src="https://img.shields.io/badge/license-MIT-green" alt="License">
  <img src="https://img.shields.io/badge/platform-android%20|%20ios-lightgrey" alt="Platform">
</p>

## 📱 Screenshots

<p align="center">
  <img src="https://github.com/username/weather-forecast-app/raw/main/screenshots/home.png" width="200" alt="Home Screen">
  <img src="https://github.com/username/weather-forecast-app/raw/main/screenshots/weather_details.png" width="200" alt="Weather Details">
  <img src="https://github.com/username/weather-forecast-app/raw/main/screenshots/settings.png" width="200" alt="Settings Screen">
  <img src="https://github.com/username/weather-forecast-app/raw/main/screenshots/dark_mode.png" width="200" alt="Dark Mode">
</p>

## 🚀 Features

- 📍 **Real-time location-based weather** - Get weather data based on your current location
- 🔍 **Search any city** - Look up weather information for any city around the world
- 🌡️ **Temperature unit toggle** - Switch between Celsius and Fahrenheit
- 🌓 **Dark mode support** - Easy on the eyes during night time
- 🔄 **Automatic refresh** - Pull to refresh for the latest weather data
- 💾 **Default city saving** - Set your favorite city as default
- 📊 **Detailed weather metrics** - View humidity, wind speed, and feels-like temperature

## 🛠️ Technology Stack

<p align="center">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/flutter/flutter-original.svg" alt="Flutter" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dart/dart-original.svg" alt="Dart" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/felangel/bloc/master/docs/assets/bloc_logo_full.png" alt="BLoC" width="80" height="40"/>
</p>

- **Flutter** - UI toolkit for building natively compiled applications
- **Dart** - Client-optimized programming language
- **BLoC Pattern** - Business Logic Component architecture for state management
- **Dio** - HTTP client for API requests
- **Geolocator** - Location services integration
- **Equatable** - Simplifies equality comparisons
- **Provider** - Dependency injection
- **Intl** - Internationalization and formatting

## 📊 Architecture & Design Patterns

### Clean Architecture

The app follows a clean architecture approach with clear separation of concerns:

```
lib/
├── bloc/         - State management logic
├── data/         - Data handling & models
├── ui/           - UI components
├── main.dart     - App entry point
```

### BLoC Pattern

The application uses not one but two BLoCs for state management:

1. **WeatherBloc** - Manages weather data fetching and state
2. **SettingsBloc** - Handles user preferences

### Immutable State Management

All states in the app are immutable, providing:
- Predictable state transitions
- Enhanced debugging capability
- Optimized rendering in Flutter

### Repository Pattern

The WeatherRepository abstracts the data source, making it easy to:
- Switch between different weather APIs
- Implement caching strategies
- Test components in isolation

## 📝 Getting Started

### Prerequisites

- Flutter SDK (v3.0.0 or higher)
- Dart SDK (v2.17.0 or higher)
- Android Studio / VS Code with Flutter extensions
- OpenWeatherMap API key

### Installation

1. Clone the repository
   ```
   git clone https://github.com/kalharawimukthi/weather-forecast-app.git
   ```

2. Navigate to the project folder
   ```
   cd weather-forecast-app
   ```

3. Install dependencies
   ```
   flutter pub get
   ```

4. Open the `lib/data/repositories/weather_repository.dart` file and replace `YOUR_API_KEY` with your OpenWeatherMap API key

5. Run the app
   ```
   flutter run
   ```

## 🔮 Future Enhancements

- 5-day weather forecast
- Weather alerts and notifications
- Weather maps integration
- Offline caching
- More detailed weather information
- Weather history

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📞 Contact

Kalhara Wimukthi - [@kalharawimukthi](https://github.com/kalharawimukthi)

---

<p align="center">
  Made with ❤️ by Kalhara Wimukthi
</p>
