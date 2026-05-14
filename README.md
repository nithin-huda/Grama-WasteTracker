# Grama Waste Tracker 🚛♻️

A modern, robust Android application designed to optimize, manage, and track waste collection processes in rural and smart village environments. This application bridges the communication gap between local residents and municipal waste management authorities, featuring real-time telemetry updates and automated dashboard reporting consoles.

## 🛠️ Tech Stack & Architecture

- **Language:** 100% Kotlin
- **UI Framework:** Jetpack Compose (Declarative UI with Material 3 Design)
- **Architecture Pattern:** MVVM (Model-View-ViewModel) with Clean Architecture principles
- **Asynchronous Flow:** Kotlin Coroutines & StateFlow for reactive data management
- **Backend Services:** Firebase Realtime Database & Firebase Authentication

---

## 🚀 Key Features

- **User & Admin Dashboards:** Separate dedicated reporting consoles optimized for citizens and regional waste management administrators.
- **Real-Time Report Tracking:** Enables residents to file disposal requests or report missed collections with dynamic state management updates.
- **Automated Background Telemetry:** Background service architecture handling reporting metrics seamlessly without compromising device performance.
- **Firebase Authentication Integration:** Secure, real-time user validation and role-based data access.

---

## 📁 Project Structure

```text
app/
└── src/
    └── main/
        └── java/com/nitin/gramawastetracker/
            ├── data/          # Firebase integration, Models, Data Repositories
            ├── ui/            # Jetpack Compose Screens, Components, Theme
            │   ├── screens/   # HomeFragment, UserDashboard, ReportFragment
            │   └── theme/     # Material 3 Design colors and typography
            └── viewmodel/     # Screen state controllers managing UI business logic
