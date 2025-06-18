# 🌦️ WeatherStarter – Swift iOS Weather App

This is the **starter project** for the workshop:

> **From Data to Design**  
> Build a Swift Weather App with API Power & Visual Polish

🎓 **Led by:** Nima – iOS Software Engineer & Tech Mentor  
🏫 **Hosted by:** Apple Developer Academy, 2025  
🛠 **Technologies:** UIKit, URLSession, Delegation, SF Symbols, PDF Assets, Auto Layout, Dark Mode, Networking

---

## 🧠 What You'll Build

This app lets users type a city name and see **live weather data** fetched from the internet, using a real API.

📦 Features you'll implement:
- Real-time API call using OpenWeatherMap
- Dynamic response to user input with `UITextFieldDelegate`
- JSON decoding with `Codable`
- UI updates on the main thread
- Dark Mode support using semantic colors
- Apple-native design polish (SF Symbols + scalable PDF backgrounds)

---

## 🚀 Getting Started

1. Click the green **"Code"** button → `Clone`
2. Open `WeatherStarter.xcodeproj` in Xcode
3. Run the app and follow along with the workshop steps

---

## 🔑 Before You Run

You'll need an API key from [OpenWeatherMap](https://openweathermap.org/current).  
Paste it inside `WeatherManager.swift`:

```swift
let weatherURL = "https://api.openweathermap.org/data/2.5/weather?appid=YOUR_API_KEY&units=metric"
