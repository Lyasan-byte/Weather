# ⛈️ WeatherApp  
*A SwiftUI weather dashboard inspired by Apple’s design language*

> This project focuses on **UI craftsmanship**: typography, color semantics, motion, layout hierarchy, and responsive interactions — not just functionality.

---

## ✨ Key Highlights

- **Apple-grade UI**: typography, spacing, symbol rendering, and visual hierarchy modeled after system apps  
- **Dynamic visuals**: temperature-driven gradients, weather-aware SF Symbols with palette rendering
- **Real weather data**: fetched from [Open-Meteo API](https://open-meteo.com) for 20 major cities worldwide  
- **Smart interactions**: tap to select city, pull-to-refresh, search, and sort (hottest → coldest)  
- **Robust networking**: async/await, error handling, task cancellation, and custom API layer  

---

## 🛠️ Tech Stack

| Layer | Technology |
|------|------------|
| **UI Framework** | SwiftUI (iOS 26+) |
| **State Management** | `@Observable`, `@Bindable` |
| **Networking** | `URLSession`, `async/await`, custom `NetworkService` protocol |
| **Data Flow** | MVVM-inspired, error mapping via `APIError` & `AlertContext` |
| **Visual Design** | SF Symbols (palette mode), linear gradients, custom typography, semantic colors |

---

## 📸 Screenshots

<div align="center">
  <img src="assets/weather in Kazan.png" width="250" alt="Weather in Kazan" />
  <img src="assets/weather in Amsterdam.png" width="250" alt="Weather in Amsterdam" />
  <br>
  <em>From left to right: Weather in Kazan, Weather in Amsterdam</em>
</div>

---

## 🚀 How to Run

1. Clone the repository  
   ```bash
   git clone https://github.com/Lyasan-byte/Weather.git
2. Open WeatherApp.xcodeproj in Xcode 26+
3. Build and run on an iOS simulator
