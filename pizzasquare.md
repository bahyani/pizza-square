#  PizzaSquare

A full-featured, cross-platform mobile food ordering and delivery application built with **React Native** and **TypeScript**. PizzaSquare delivers a seamless end-to-end customer experience—from browsing menus and tracking live deliveries to seamless in-app payments, digital receipts, and real-time customer support.

> **Note:** This repository serves as a public showcase and release hub for **PizzaSquare**. The proprietary source code is maintained in a private repository.

---

##  Key Features

* **Secure Authentication & Onboarding:** Smooth user registration and verification powered by OTP entry and input validation.
* **Interactive Maps & Geolocation:** Real-time location detection, delivery address pinning, and live order tracking via Google/Apple Maps.
* **Seamless Checkout & Payments:** Integrated **Paystack** checkout flow for fast, secure mobile payments alongside coupon/promo code support.
* **Digital Receipts & Barcodes:** Automated PDF receipt generation, mobile printing support, and scannable order/loyalty barcodes.
* **In-App Customer Support:** Real-time chat interface for instant order assistance and customer inquiries.
* **Smart Push Notifications:** Instant order status updates, delivery alerts, and promotional notifications.
* **Offline-First Persistence:** Local data caching and storage using SQLite and AsyncStorage for fast load times and reliable cart state.
* **Rich Media & Modern UI:** Smooth bottom sheets, multi-slider filters, video showcases, linear gradients, and intuitive tab/stack navigation.

---

## Tech Stack & Architecture

| Category | Technologies |
| :--- | :--- |
| **Core Framework** | React Native (`0.74.7`), React (`18.2.0`), TypeScript (`5.0.4`) |
| **Navigation** | React Navigation v7 (Native Stack, Bottom Tabs, Tab View) |
| **Payments** | Paystack WebView (`react-native-paystack-webview`) |
| **Maps & Location** | `react-native-maps`, `@react-native-community/geolocation` |
| **Networking & Data** | Axios, SQLite (`react-native-sqlite-storage`), AsyncStorage |
| **Notifications** | Notifee (`@notifee/react-native`), `react-native-push-notification` |
| **Documents & Media** | `react-native-html-to-pdf`, `react-native-print`, Barcode Generator, `react-native-video` |
| **UI & Interactions** | Gesture Handler, Raw Bottom Sheet, Vector Icons, Linear Gradient, Gifted Chat |

---

## App Preview

<!-- Replace the placeholders below with screenshots or a screen recording GIF of your app -->
| Home & Menu | Live Map & Tracking | Checkout & Receipt |
| :---: | :---: | :---: |


---

## Download & Releases

Compiled builds (`.apk` / `.ipa`) and test releases are available in the **[Releases](../../releases)** section of this repository.

### Supported Platforms
* **Android:** Android 7.0 (API 24) and above
* **iOS:** iOS 13.4 and above

---

## 📬 Contact & Inquiries

For demo access, business inquiries, or feedback regarding **PizzaSquare**, please open an issue in this repository or reach out directly via GitHub.
