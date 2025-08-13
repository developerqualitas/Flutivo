# **Flutivo** 🚀

*Flutter your way into innovation.*

Flutivo is a **feature-rich playground app** built with Flutter. It’s designed as a **dummy testing application** where developers can explore, experiment, and implement various mobile app features in one place — from listings to notifications, location tracking, and connectivity checks.

---

## 📌 **Features**

* **📋 Listings Module** — Display, search, and filter data lists with pagination.
* **🔔 Notifications** — Push and in-app notification system.
* **🌐 Connectivity Check** — Detect online/offline status and show alerts.
* **📍 Location Services** — Fetch and display the user’s current location.
* **🧾 Ticket Management** — Create, update, and view ticket details (example workflow).
* **🎨 Modern UI** — Responsive, adaptive design using Flutter’s best practices.
* **🧪 Dummy Data Support** — Preloaded JSON data for testing without a backend.

---

## 🛠 **Tech Stack**

* **Framework:** Flutter (latest stable version)
* **State Management:** `flutter_bloc`
* **Routing:** `go_router`
* **UI Scaling:** `flutter_screenutil`
* **Notifications:** `firebase_messaging` / Local notifications
* **Location:** `geolocator`
* **Connectivity:** `connectivity_plus`
* **SVG Support:** `flutter_svg`

---

## 📂 **Folder Structure**

```
lib/
│
├── app/
│   ├── dashboard/       # Main dashboard & feature navigation
│   ├── listings/        # List & search example
│   ├── notifications/   # Notifications module
│   ├── location/        # Location check example
│   ├── connectivity/    # Connectivity checker
│   ├── tickets/         # Ticket management workflow
│
├── core/
│   ├── common/          # Constants, styles, paths
│   ├── utils/           # Helpers & utilities
│
└── main.dart
```

---

## 🚀 **Getting Started**

### 1️⃣ **Clone the Repository**

```bash
git clone https://github.com/your-username/flutivo.git
cd flutivo
```

### 2️⃣ **Install Dependencies**

```bash
flutter pub get
```

### 3️⃣ **Run the App**

```bash
flutter run
```

---

## 🔮 **Planned Features**

* Authentication flow (Login/Register)
* Dark mode support
* API integration example
* Offline mode with local storage

---

## 🤝 **Contributing**

We welcome contributions! Fork the repo, create a new branch, and submit a pull request.

---

## 📜 **License**

This project is licensed under the MIT License.
