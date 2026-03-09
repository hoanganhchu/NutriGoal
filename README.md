# NutriGoal

A mobile app for tracking nutrition, discovering food categories, and creating personal recipes — built with React Native and TypeScript.

---

## Features

- **Onboarding & Data Collection** — Personalized setup based on user health data
- **Food Categories** — Browse and explore foods by category
- **Nutrition Formulas** — Calculate nutritional needs based on personal metrics
- **Recipe Creation** — Create and save custom recipes
- **Blog & Articles** — View nutrition-related content
- **User Profile** — Manage personal information and goals

---

## Tech Stack

| | |
|---|---|
| Framework | React Native (TypeScript) |
| Navigation | React Navigation (Native Stack + Bottom Tab) |
| State Management | React Context API |
| Data | Local JSON (nutrition database) |

---

## Getting Started

### Prerequisites
- Node.js 18+
- React Native environment setup ([guide](https://reactnative.dev/docs/environment-setup))
- Xcode (iOS) or Android Studio (Android)

### Installation

```bash
git clone https://github.com/hoanganhchu/NutriGoal.git
cd NutriGoal
npm install
```

### Run on iOS
```bash
npm run ios
```

### Run on Android
```bash
npm run android
```

---

## Project Structure

```
NutriGoal/
├── screens/          # App screens (Home, Login, CatePage...)
├── assets/           # Styles, components, BottomTab
├── data/             # Store (Context) + nutrition JSON data
├── App.tsx           # Root navigator
```

---

## Author

Built independently with mentorship support.
