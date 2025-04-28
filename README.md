# Habit Buddy - README
Author: Alex Nguyen 


## 📱 Overview
Habit Buddy is a mobile app designed to help users build better habits through motivation, tracking, and gamified challenges. It was developed as part of CMSC 427 Homework 11 and demonstrates interactive mobile design using React Native and Expo Snack.

## 🚀 Features
- ✅ Tap-to-complete daily habit tracking
- 📊 Weekly progress visualized with streaks and emoji feedback
- 🎯 Challenges with editable goals and progress updates
- 💬 Motivational quotes pulled from the API Ninjas Quotes API
- 🌙 Toggleable dark mode and placeholder settings pages

## 🛠️ Technologies
- React Native (via Expo Snack)
- React Navigation (stack + tabs)
- React hooks: `useState`, `useEffect`, `useContext`
- API call to [api.api-ninjas.com/v1/quotes](https://api-ninjas.com/api/quotes)

## 🔧 Setup Instructions
1. Open in Snack: [https://snack.expo.dev/@alekay/habit-buddy](https://snack.expo.dev/@alekay/habit-buddy)
2. Modify screens in the `App.js` file or extract to components as needed.
3. Replace API key with your own in the Home screen fetch logic for quotes.

## 📂 App Structure
```
App.js                  # Main logic and navigation
/components             # Each screen stored as a tab or stack view
/assets                 # Screenshots and wireframes used for documentation
/report/report.qmd      # Quarto report with write-up and reflections
```

## ✨ Screens Implemented
- Home
- Challenges
- Streaks & Progress
- Settings (with subpages)

## 📈 Reflections
This app emphasized the importance of component structure, clean design, and managing global state. Hooks and Snack were powerful tools, and the iterative feedback helped refine each feature.

## 📎 Links
- GitHub: [cmsc427-sp2025-hw11-AlekayPrograms](https://github.com/cmsc-vcu/cmsc427-sp2025-hw11-AlekayPrograms)
- Snack: [Habit Buddy on Snack](https://snack.expo.dev/@alekay/habit-buddy)
- Figma: [Wireframes + Storyboard](https://www.figma.com/board/1ZPKugOH79G67V9fVxGRkA/Habit-Buddy?node-id=0-1)