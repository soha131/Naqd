# Naqd - Smart Expense Tracking App 💰

Smarter Tracking, Better Living

---

## 🧭 Overview

Naqd is a sophisticated expense tracking mobile application built with Flutter that leverages AI-powered receipt scanning to automatically detect spending amounts. The app features dual account modes (Personal & Corporate) with Firebase backend integration, making expense management seamless and intelligent.

## Key Highlights

  🤖 AI-Powered OCR: Automatically extract total amounts from receipt images
  
  👤 Dual Account Types: Switch between Personal and Corporate spending modes
  
  📊 Visual Analytics: Interactive charts and spending trends
  
  🔐 Secure Authentication: Google Sign-In, Email/Password, and Phone authentication
  
  ☁️ Cloud Sync: Real-time data synchronization with Firebase
  
  📱 Cross-Platform: Built with Flutter for iOS and Android
---

## ✨ Key Feature
   •	 Automatic amount detection via OCR API
   
   •	 Transaction history with filtering
   
   •	 Track expense status (Pending, Approved, Rejected, Needs Info)
   
   •	 Add expenses manually or via receipt scanning
   
   •	 View spending trends with interactive charts
   
---

## 🛠️ Tech Stack
   - Frontend
      •	Flutter - Cross-platform mobile framework
     
      •	State Management:
          BLoC/Cubit for business logic
          Provider for theme management
     
      •	FL Chart - Data visualization library
     
   - Backend & Services
      •	Firebase Authentication - User authentication with email/password
     
      •	Cloud Firestore - NoSQL database for real-time data
          
      •	Custom OCR API - Receipt scanning and amount extraction
     


---
## 🪄 App Preview

![App Demo](assets/.gif)

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/soha131/Naqd.git
```

### 2. Install Dependencies
```bash
flutter pub get
```

### 3. Run the App
```bash
flutter run
```

> Make sure your environment is set up with Flutter SDK.

---

## 🧩 Folder Structure

```

lib/
├── auth/                    # Authentication screens
│   ├── email_login.dart
│   ├── login_in.dart
│   └── signup.dart
├── personal/                # Personal account features
│   ├── personal_main.dart
│   ├── personal_account.dart
│   ├── personal_trend.dart
│   ├── add_spending_personal.dart
│   └── spending_add.dart
├── coorporate/              # Corporate account features
│   ├── coorporate_main.dart
│   ├── coorporate_account.dart
│   ├── add_spending_coorporate.dart
│   ├── Cspending_add.dart
│   └── Expense_States.dart
├── cubit/                   # State management
│   ├── SpendingCubit.dart
│   ├── CoorporateCubit.dart
│   ├── ocr_cubit.dart
│   ├── ocr_model.dart
│   ├── ocr_state.dart
│   └── service.dart
├── splash/                  # Onboarding screens
│   ├── loading.dart
│   ├── welcome.dart
│   └── main_page.dart
├── widget/                  # Reusable components
│   └── background.dart
├── SpendingService.dart     # Business logic
├── firebase_options.dart    # Firebase configuration
└── main.dart               # App entry point

```


---
## 📅 Future Enhancements
   -  Social sharing of spending insights
   -  Push notifications for spending alerts
   -  Budget recommendations using ML
   -  Export transactions to PDF/Excel

---
---

## 📸 Screenshots




---

## 🤝 Contributing

Contributions are welcome!  
Please open an issue or submit a pull request to help improve the project.

---

## 📄 License

This project is licensed under the **MIT License** — feel free to use and modify it.

---
