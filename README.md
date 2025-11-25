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

