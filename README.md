# E-Agribusiness Mobile Application (Android + Firebase)

A modern mobile application designed to support farmers with digital
agriculture tools including:

- Farmer registration and authentication
- Crop/product listings
- Buying and selling marketplace
- Real-time market price dashboard
- User profile management
- Firebase cloud backend

---

## 💡 Features

### 1. Authentication
- Email/password login
- Secure registration using Firebase Authentication
- Firestore user profiles with name + email

### 2. Dashboard
- Personalized greeting
- Quick access tiles for:
  - Sell Products
  - Buy Products
  - Market Prices
  - My Listings
  - Profile
  - Logout

### 3. Sell Products
Farmers can upload:
- Crop image
- Name
- Price
- Description  
Data is saved to:
- Firebase Firestore (text)
- Firebase Storage (images)

### 4. Buy Products
Displays marketplace of all posted crops with:
- Image
- Price
- Seller contact
- Auto-update on new listings

---

## 🛠 Tech Stack

| Layer | Technology |
|------|------------|
| Frontend UI | Jetpack Compose |
| App Logic | Kotlin |
| Navigation | Jetpack Navigation Compose |
| Backend | Firebase (Auth, Firestore, Storage) |
| Build System | Kotlin DSL + AGP 8.1 |

---

## 📁 Project Structure
app/
├── ui/
│ ├── LoginScreen.kt
│ ├── RegisterScreen.kt
│ ├── DashboardScreen.kt
│ ├── SellScreen.kt
│ ├── BuyScreen.kt
│ ├── ProfileScreen.kt
│ └── components/
│ └── ProductCard.kt
├── data/
│ ├── models/
│ └── repository/
└── navigation/
└── AppNavigation.kt

---

## 🚀 Installation

1. Clone the project  
   `git clone https://github.com/yourusername/E-Agribusiness-App.git`

2. Open using Android Studio 2025.2 (Koala)

3. Ensure:
   - compileSdk = 36
   - Kotlin = 2.0.21
   - Firebase BOM = 34.6.0

4. Add your `google-services.json` in:

5. Run app on a device or emulator.

---

## 📦 Signed APK

The signed APK is located under:


To generate your own:
Android Studio → Build → Generate Signed App Bundle / APK  
Select → APK  
Create keystore → Sign → Finish

---

## 📹 Demo Video Script

See `demo_video_script.txt` in the repo.

---

## 📄 Project Report

See `PROJECT_REPORT.pdf` for methodology, architecture, screenshots,
implementation, challenges, and future improvements.

---

## 👤 Author
Jackson Mamboleo  
E-Agribusiness App Developer  
2025

