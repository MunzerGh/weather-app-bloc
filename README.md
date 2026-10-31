# 🌤️ Flutter Weather App (BLoC/Cubit Refactored)

A modern weather application built with Flutter, showcasing state management using **BLoC / Cubit** alongside clean architecture and dynamic UI themes.

## ✨ Features
- **Real-Time Weather Search:** Search for current weather conditions, temperatures, and forecasts for any city.
- **Dynamic UI Theming:** The app background and theme gradients dynamically adapt based on the weather condition and temperature.
- **Robust State Management:** Powered by `flutter_bloc` to cleanly handle distinct application states (`WeatherInitial`, `WeatherLoading`, `WeatherSuccess`, `WeatherFailure`).
- **Clean Architecture:** Strict separation of concerns between UI presentation, business logic (Cubit), and network services.

## 📂 Project Structure
```text
lib/
├── cubites/
│   └── weather_cubit/
│       ├── weather_cubit.dart
│       └── weather_state.dart
├── models/
│   └── weather_model.dart
├── pages/
│   ├── home_page.dart
│   └── search_page.dart
├── services/
│   └── weather_service.dart
└── main.dart
🛠️ Tech Stack
Framework: Flutter & Dart

State Management: flutter_bloc (Cubit)

Networking: HTTP / Dio for fetching weather data from APIs

UI & Styling: Custom LinearGradients, responsive layouts, and Material Design

🚀 Getting Started
To get a local copy up and running, follow these simple steps:

Prerequisites
Make sure you have the Flutter SDK installed on your machine.

Installation
Clone the repository:

Bash
git clone [https://github.com/MunzerGh/weather-app-bloc.git](https://github.com/MunzerGh/weather-app-bloc.git)
Navigate to the project directory:

Bash
cd weather-app-bloc
Install dependencies:

Bash
flutter pub get
Run the application:

Bash
flutter run
⭐ Feel free to fork or star this repository if you find it helpful!