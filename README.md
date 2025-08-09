# 🌦️ WeatherApp

![Kotlin](https://img.shields.io/badge/Kotlin-0095D5?style=for-the-badge&logo=kotlin&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![MVVM](https://img.shields.io/badge/MVVM-FF6F00?style=for-the-badge&logo=android&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

> **A clean and functional weather forecasting app** created as a practical exercise in mastering native **Android development** with **Kotlin** and **Jetpack Compose** ☀️🌧️

---

## 🎯 Project Goal

This project focuses on **fetching and displaying location-based data** from a real-world API. It demonstrates the use of modern Android development techniques to create a **visually appealing and useful utility application**.

---

## ✨ Features

- **🌡️ Current Weather** — Fetches and displays current weather conditions for any city
- **📊 Weather Metrics** — Shows key data like temperature, humidity, and wind speed  
- **🎨 Beautiful UI** — Declarative UI built from scratch with **Jetpack Compose**
- **⚡ Asynchronous Updates** — Fetches data without blocking the main thread
- **🔄 Real-time Data** — Live weather updates from OpenWeatherMap API
- **📱 Modern Design** — Clean, intuitive interface following Material Design

---

## 🛠️ Tech Stack & Key Concepts

| Technology | Description |
|------------|-------------|
| **🔤 Language** | [Kotlin](https://kotlinlang.org/) |
| **🎨 UI Toolkit** | [Jetpack Compose](https://developer.android.com/jetpack/compose) |
| **🏗️ Architecture** | MVVM (Model-View-ViewModel) |
| **⚡ Async Programming** | Kotlin Coroutines and `StateFlow` |
| **🌐 Networking** | [Ktor Client](https://ktor.io/docs/client-overview.html) |
| **🗂️ State Management** | Managed within `ViewModel` for UI consistency |

---

## 📡 API Integration

This app gets its data from the **[OpenWeatherMap API](https://openweathermap.org/api)**

| Endpoint | Description | Usage |
|----------|-------------|-------|
| **Current Weather** | `/weather` | Get current weather conditions 🌤️ |
| **Weather Data** | Real-time metrics | Temperature, humidity, wind speed 📊 |

> 🔑 **Important:** You will need your **own API key** to build and run the project!

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/WeatherApp.git
cd WeatherApp
```

### 2️⃣ Get Your API Key
1. 🔐 **Sign up** at [OpenWeatherMap](https://openweathermap.org/api)
2. 📋 **Copy your API key** from the dashboard
3. 📝 **Add to your project** (see configuration below)

### 3️⃣ Configure API Key
Create a `local.properties` file in your project root:
```properties
API_KEY="your_openweathermap_api_key_here"
```

### 4️⃣ Open in Android Studio
- 📂 Launch **Android Studio**
- 🔍 Choose **Open an Existing Project**
- 📁 Select the cloned directory

### 5️⃣ Build & Run
```bash
./gradlew assembleDebug
```
Or click the **Run** ▶️ button in Android Studio

---

## 🏗️ Architecture Overview

```
WeatherApp/
├── 📁 data/
│   ├── 🌐 remote/ (API services)
│   ├── 📄 models/ (Data classes)
│   └── 🗂️ repository/ (Data layer)
├── 📁 ui/
│   ├── 🎨 compose/ (UI components)
│   ├── 📱 screens/ (App screens)
│   └── 🎭 theme/ (Material theme)
├── 📁 viewmodel/
│   └── 🧠 WeatherViewModel.kt
└── 📄 MainActivity.kt
```

---

## 📱 Key Weather Metrics

| Metric | Display | Description |
|--------|---------|-------------|
| 🌡️ **Temperature** | °C / °F | Current temperature |
| 💧 **Humidity** | % | Air moisture level |
| 💨 **Wind Speed** | km/h | Wind velocity |
| 🌤️ **Conditions** | Icon + Text | Weather description |
| 👁️ **Visibility** | km | Atmospheric visibility |
| 📊 **Pressure** | hPa | Atmospheric pressure |

---

## 📷 Screenshots

<table>
  <tr>
    <th>🏠 Main Screen</th>
    <th>🔍 Search City</th>
    <th>📊 Weather Details</th>
  </tr>
  <tr>
    <td align="center">
      <img src="https://via.placeholder.com/200x400" alt="Main Weather Screen" width="200" />
      <br>
      <em>Current Weather Display</em>
    </td>
    <td align="center">
      <img src="https://via.placeholder.com/200x400" alt="City Search" width="200" />
      <br>
      <em>City Search Interface</em>
    </td>
    <td align="center">
      <img src="https://via.placeholder.com/200x400" alt="Weather Details" width="200" />
      <br>
      <em>Detailed Weather Info</em>
    </td>
  </tr>
</table>

---

## 🎯 Learning Objectives

- ✅ **API Integration** — Working with real-world REST APIs
- ✅ **Jetpack Compose** — Modern declarative UI development  
- ✅ **MVVM Architecture** — Separation of concerns and testability
- ✅ **Coroutines** — Asynchronous programming in Kotlin
- ✅ **State Management** — Reactive UI updates with StateFlow
- ✅ **Error Handling** — Graceful API failure management

---

## 🤝 Contributing

This is a **learning project**, but improvements are welcome!

1. 🍴 **Fork** the repository
2. 🌿 **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. 💾 **Commit** changes (`git commit -m 'Add amazing feature'`)
4. 📤 **Push** to branch (`git push origin feature/amazing-feature`)
5. 🔄 **Open** a Pull Request

---

## 📜 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

## 🙌 Acknowledgments

- 🌦️ **OpenWeatherMap API** for providing reliable weather data
- 🎨 **Jetpack Compose** for the amazing declarative UI toolkit
- ⚡ **Kotlin Coroutines** for seamless asynchronous programming
- 🏗️ Built with ❤️ for **learning modern Android development**

---

## 🔗 Quick Links

- 📜 [MIT License](LICENSE)
- 🌦️ [OpenWeatherMap API Docs](https://openweathermap.org/api)
- 🎨 [Jetpack Compose Docs](https://developer.android.com/jetpack/compose)
- ⚡ [Kotlin Coroutines Guide](https://kotlinlang.org/docs/coroutines-guide.html)
- 🌐 [Ktor Client Documentation](https://ktor.io/docs/client-overview.html)

---

*⭐ **Star this repo** if it helped you learn Android development with Kotlin & Compose!*
