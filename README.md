# 🥗 The Burn Rate (TBR)

### *Stop counting calories. Start counting life.*

**The Burn Rate** is an Android application that translates abstract nutritional data into **Human Activity Units**. Instead of showing you a number like "400 calories," TBR tells you exactly how many hours of your life that food fuels—whether you're just existing, walking the dog, or gaming.

---

## 🚀 The Concept

Most people don't know what a calorie "feels" like. This app gamifies nutrition by converting food energy into time-based metrics using the **MET (Metabolic Equivalent of Task)** formula:

---

## ✨ Features

* **LENS Scanner:** Instant barcode and AI image recognition for food items.
* **The Life-Clock:** Displays how many hours you could survive on a specific snack if you were just lying in bed (Basal Metabolic Rate).
* **Activity Swapper:** Toggle between different "burn" activities (Running, Gaming, Scrubbing Floors, Walking).
* **Personalized Metabolism:** Syncs with **Android Health Connect** to use your real weight and activity data for precision.
* **The "Worth It?" Gauge:** A visual indicator comparing the pleasure of the snack to the "cost" in movement.

---

## 🛠️ Tech Stack (2026 Edition)

* **Language:** Kotlin
* **UI:** Jetpack Compose (Declarative UI)
* **Core:** Android Architecture Components (ViewModel, LiveData, Room)
* **Intelligence:** Google ML Kit (Barcode Scanning) & Gemini Flash API (Food Recognition)
* **Data:** Nutritionix API & Health Connect

---

## 🗺️ Development Roadmap

### Phase 1: The Foundation (MVP) 🏗️

* [ ] User Onboarding: Profile setup (Weight, Age, Sex).
* [ ] Core Engine: Implementation of the MET calculation logic.
* [ ] Manual Entry: Users can type in a calorie count to see the "Time-Units" instantly.

### Phase 2: The Vision 👁️

* [ ] Barcode Integration: Scan store-bought items via Google ML Kit.
* [ ] API Connectivity: Live fetching of nutritional data from Nutritionix.
* [ ] Basic Activity List: Walking, Running, and "Existing" (BMR).

### Phase 3: AI & Customization 🧠

* [ ] Image Recognition: Take a photo of a plate of food (no barcode) to estimate calories.
* [ ] Custom Activities: Add "Niche" burns (e.g., "Hours of VR Gaming" or "Mowing the Lawn").
* [ ] Health Connect Sync: Automatically update user weight from smart scales/Fitbit.

### Phase 4: Social & Gamification 🏆

* [ ] "Burn Challenges": Challenge friends to "Walk off a Pizza."
* [ ] Weekly Insights: "This week you fueled 14 hours of hiking."
* [ ] Home Screen Widgets: Quick-scan from the Android home screen.

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
