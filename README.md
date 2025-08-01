# Auth Dashboard App 🚀  

**A Kotlin Android App using MVVM + Jetpack Compose + Retrofit**  
📌 Developed by **Oviya Punniyamoorthy**

## 📲 Overview

This is a modern Android application that demonstrates basic **authentication flow** and a **dynamic dashboard**, built using the **MVVM (Model-View-ViewModel)** architecture.  
The project uses **Retrofit** to fetch user data and **Jetpack Compose** for clean and responsive UI.

It includes:

- ✅ Splash Screen (2 sec delay)  
- 🔐 Forgot Password screen with reset confirmation  
- 📊 Interactive Dashboard showing data from a remote API  
- 📦 Full MVVM pattern with Retrofit and Compose  
- 🧪 Snackbar messages for success & error states

---

## 🌟 Features

| Feature                | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| 🔓 Login Flow          | Simple login screen with navigation support                                 |
| ✉️ Forgot Password     | Email input field with Snackbar confirmation: _"Reset link sent"_            |
| 📁 Dashboard           | Fetches and displays Name, Email, City from public API                      |
| 🚀 API Integration     | Uses `https://jsonplaceholder.typicode.com/users` with Retrofit              |
| 🧱 MVVM Architecture   | Clean separation of concern using ViewModel, Repository, and UI Layer        |
| 🎨 Jetpack Compose UI  | All screens built using Jetpack Compose (bonus inclusion)                   |
| 📢 Snackbar Feedback   | Displays visual messages for success and error states                       |
| ↩️ Navigation          | Seamless screen transition (Forgot password ↔ Login ↔ Dashboard)             |

---

## 🧰 Tech Stack

- 💻 Language: **Kotlin**
- 🧩 Architecture: **MVVM**
- 📦 Network: **Retrofit**
- 🖼 UI: **Jetpack Compose**
- 🔁 Data Flow: **LiveData / State**
- 🧪 Tools: Android Studio, Emulator

---

---

## 🖼 Preview Video

https://drive.google.com/file/d/1E_KsevNByg52zsvuID2k-MPOoxwiyO07/view?usp=sharing

---

## 🖼 APK Drive Link

https://drive.google.com/file/d/1XfG_uHLTZbiuCEUlLS7VdQ53N-SydnYy/view?usp=drive_link

---

## 🖼 Screens Included

1. **SplashScreen** – Shows app splash with a 2-second delay  
2. **LoginScreen** – Basic login UI  
3. **ForgotPasswordScreen** – Email input + Snackbar feedback  
4. **DashboardScreen** – Lists user data from API  
5. **Navigation** – Jetpack Compose navigation for screen transition

---

## 🔗 API Used

Fetched data from:

```bash
https://jsonplaceholder.typicode.com/users
