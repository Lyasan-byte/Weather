# ⛈️ WeatherApp  
*A SwiftUI weather dashboard inspired by Apple’s design language*

**WeatherApp** is built to demonstrate deep understanding of **Apple’s Human Interface Guidelines** and modern **SwiftUI capabilities**. It fetches real-time weather for 20 global cities and presents data through highly intentional interface — all designed to feel like a native Apple experience.

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

##  Screenshots

<div align="center">
  <img src="screenshot1.png" width="250" alt="Main Weather View" />
  <img src="screenshot2.png" width="250" alt="City List with Gradients" />
  <img src="screenshot3.png" width="250" alt="Search & Sorting" />
  <br>
  <em>From left to right: Current weather, city list with temp gradients, interactive controls</em>
</div>

---

## 🚀 How to Run

1. Clone the repository  
   ```bash
   git clone https://github.com/Lyasan-byte/Weather.git
2. Open WeatherApp.xcodeproj in Xcode 26+
3. Build and run on an iOS simulator
