# Tracker
So private not for you
# 📍 Dad Tracker (Live Location Web App)

A simple real-time location tracking web app using **Firebase Realtime Database** and **JavaScript**.

## 🚀 Features
- 📍 Live location tracking
- ⚡ Real-time updates using Firebase
- 🌐 Works on any browser (GitHub Pages)
- 🔒 Private usage (only you & your dad)

---

## 🛠️ Tech Used
- HTML, JavaScript
- Firebase Realtime Database
- GitHub Pages

---

## 📂 Files
- dad.html → Sends live location
- dashboard.html → Displays location data

---

## ⚙️ Setup

### 1. Firebase Setup
- Create Firebase project
- Enable **Realtime Database**
- Set rules:

```json
{
  "rules": {
    ".read": true,
    ".write": true
  }
}
