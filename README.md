# 🔋 System Battery Checker

A simple, elegant, and responsive web app to monitor your device's battery status using the Battery Status API. Built using HTML, CSS, and JavaScript.

## 🌟 Features

- 🔋 Shows current battery percentage with a visual progress bar
- ⚡ Displays charging status (connected/disconnected)
- ⏳ Estimates remaining or charging time
- 🪫 Low battery warning when charge drops below 30%
- ✅ Clean, mobile-friendly UI

## 🚀 Live Demo

[Click to try it out!](https://n2023ik.github.io/system-battery-cheker/)  


## 📸 Screenshots

![Screenshot](https://github.com/n2023ik/system-battery-cheker/blob/main/batery.png?raw=true)  


## 📦 Tech Stack

- HTML5
- CSS3 (with custom styling and gradients)
- JavaScript (ES6+)
- Battery Status API

## 📋 How It Works

The app uses `navigator.getBattery()` to fetch battery information and dynamically updates:

- The battery level bar
- Charging status text and color
- Battery icon (emoji)
- Estimated remaining or charging time

If the user's browser doesn't support the Battery Status API, a fallback message is shown.

