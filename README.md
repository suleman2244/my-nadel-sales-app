# my-nadel-sales-app
**JNI Sales App** is an **enterprise-grade sales management application** developed for a private client using **Flutter** and **BLoC** state management.   The app is a **web-first solution wrapped as a mobile application**, designed for internal use by the client’s sales team. 


> ⚠️ This is a **client-exclusive application** and not publicly available.

---

## 📱 Overview

JNI Sales App empowers sales teams to:

- Manage customer accounts and contacts  
- Create and track sales orders  
- View and manage product catalogs  
- Access analytics and reports  
- Operate offline with automatic synchronization to backend D365 services  

The app is wrapped as a mobile application, allowing teams to use it on both Android and iOS devices, while maintaining enterprise-level security and performance.

---

## 👨‍💻 My Role – Lead Flutter Developer

As the **Lead Flutter Developer**, I was responsible for:

- Designing the **application architecture** using Flutter and BLoC for scalable state management.  
- Wrapping a **web application into a mobile app** using Flutter’s WebView and hybrid techniques.  
- Implementing **BLoC state management** to handle all app states efficiently and predictably.  
- Integrating the app with **Microsoft Dynamics 365 (D365) services** for orders, customers, and product data.  
- Implementing **offline-first functionality**, allowing sales reps to create and save orders without internet connectivity.  
- Developing reusable **UI components** following client branding guidelines.  
- Ensuring **responsive UI** across multiple mobile device sizes and orientations.  
- Leading a team of developers, performing **code reviews**, and enforcing best practices.  
- Optimizing performance for both web and mobile builds.  
- Coordinating with backend teams and business analysts for seamless integration with D365.

---

## 🧩 Core Features

- 🧾 **Order Management:** Create, edit, and track sales orders.  
- 🧍 **Customer Management:** Access detailed customer information and purchase history.  
- 📦 **Product Catalog:** View and select from client-specific products synced with D365.  
- ☁️ **Offline Mode:** Orders can be created offline and synchronized when connectivity is restored.  
- 📊 **Reports & Analytics:** View sales reports and performance dashboards.  
- 🔒 **Role-Based Access:** Ensures secure login and permissions for different user roles.  
- 🌐 **Web & Mobile:** Web application wrapped as a mobile app for Android and iOS deployment.

---

## ⚙️ Tech Stack

| Category | Technology |
|-----------|-------------|
| **Frontend Framework** | Flutter |
| **State Management** | BLoC (flutter_bloc) |
| **Backend Services** | Microsoft Dynamics 365 (D365) |
| **APIs** | RESTful APIs |
| **Offline Storage** | Hive / SharedPreferences |
| **Authentication** | OAuth 2.0 / JWT |
| **Build & Deployment** | Flutter Web + Mobile (Android/iOS) |
| **Version Control** | Git + GitHub / Azure DevOps |

---

## 🏗️ Folder Structure

jni-sales-app/
│
├── lib/
│ ├── blocs/ # BLoC state management
│ ├── components/ # Reusable UI components
│ ├── pages/ # App screens (Orders, Customers, Dashboard)
│ ├── services/ # API services and D365 integration
│ ├── utils/ # Utility functions and constants
│ ├── main.dart
│ └── app_router.dart
│
├── web/ # Flutter web project for internal use
├── assets/ # Icons, images, fonts
├── test/ # Unit and widget tests
└── README.md





---

## 🔐 Key Integrations

- **Microsoft Dynamics 365 (D365)** – Core backend for order, customer, and product management.  
- **Offline Storage** – Allows sales reps to create orders offline using Hive or SharedPreferences.  
- **Secure Authentication** – OAuth2 / JWT-based login for enterprise-grade security.  
- **Hybrid Web + Mobile** – Web app wrapped in Flutter mobile application for cross-platform deployment.  

---

## 🧱 Architecture Highlights

- **Flutter + BLoC pattern** for predictable, testable state management.  
- **Modular and component-based UI** for easy maintenance and scalability.  
- **Service-oriented integration** with D365 backend.  
- **Offline-first design** for field sales operations.  
- **Enterprise security** with token-based authentication and role-based access.

---

## ⚙️ Installation & Development Setup

> ⚠️ Requires **client credentials and D365 API access**.

```bash
# Clone repository
git clone https://github.com/yourusername/jni-sales-app.git

# Navigate to project
cd jni-sales-app

# Install dependencies
flutter pub get

# Run app on web
flutter run -d chrome

# Run app on Android
flutter run -d android

# Run app on iOS
flutter run -d ios
