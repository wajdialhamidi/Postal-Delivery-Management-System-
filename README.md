# 📦 Postal Delivery Management System

## 📱 Overview
**Postal Delivery Management System (2022)** is a comprehensive Android mobile application designed to simplify and digitalize the **parcel delivery workflow**.  
Through this app, users can easily **create, track, and manage shipments**, define pickup and delivery locations, specify package details, and monitor delivery status — all in one place.

The system aims to make the delivery process **efficient, transparent, and user-friendly**, providing end-to-end visibility for both users and the delivery company.

---

## 🚀 Key Features

### 👤 User Features
- 🔐 **User Authentication** — Secure login and registration for users.
- 🏠 **Home Dashboard** — Access all delivery-related actions from one central screen.
- 📬 **Create New Shipment**  
  - Define **pickup location** and **delivery destination** using interactive maps or address input.  
  - Enter detailed **package information** such as weight, dimensions, and package type.  
  - Confirm shipment details before sending.
- 📦 **Package Details Entry** — Specify height, width, weight, and any special handling notes.
- ✅ **Shipment Confirmation Screen** — Review all details before finalizing the request.
- 🚚 **My Parcels Section** — View all shipments created by the user, including their current **delivery status**.
- 📍 **Live Tracking** — Track delivery progress and see real-time updates of the parcel’s route.
- 🔔 **Status Updates** — Get notified when your package is picked up, in transit, or delivered.
- 📑 **Delivery History** — Access past shipments and their delivery details.

---

### 🚗 Delivery Management (For Delivery Company)
- 🗺️ **Route Optimization** — Assign drivers optimal delivery routes for faster delivery.
- 🕒 **Real-Time Status Updates** — Update shipment status instantly (Picked up, In Transit, Delivered).
- 👨‍💼 **Delivery Personnel Dashboard** — Manage daily assigned deliveries efficiently.
- 📊 **Reports & Analytics** — Overview of total deliveries, active shipments, and performance metrics.

---

## ⚙️ How It Works
1. The user **logs into the app** or creates a new account.  
2. On the **main screen**, the user clicks "Create Parcel".  
3. The app allows the user to **choose pickup and delivery locations**.  
4. Next, the user defines **package specifications** (dimensions, weight, etc.).  
5. The user is then shown a **confirmation screen** to verify all details.  
6. After confirmation, the shipment is created and assigned a tracking number.  
7. The user can monitor the **delivery status** in real time under “My Parcels”.
8. Delivery staff update the shipment’s progress via the company dashboard or API.

---

## 🛠️ Technologies Used
| Component | Technology |
|------------|-------------|
| **Frontend (Mobile App)** | Java (Android SDK) |
| **Networking** | Retrofit / Volley for API Integration |
| **Database** | SQLite (Local Storage) |
| **Maps & Location** | Google Maps API for location and route selection |
| **Authentication** | Secure Login / API-based Authentication |
| **Backend Integration** | REST APIs for shipment management and tracking |
| **Version Control** | Git & GitHub |
| **IDE** | Android Studio |

---

## 🧠 Purpose
The system was built to **modernize postal delivery operations**, enabling customers to create and manage shipments directly through their smartphones.  
It eliminates manual paperwork and provides **transparency, convenience, and accuracy** for both senders and delivery companies.

---

## 👨‍💻 My Role
I was responsible for:
- Designing and developing the **Android mobile app** using Java.  
- Implementing **user registration, login, and shipment creation workflows**.  
- Integrating **Google Maps API** for location selection and tracking.  
- Developing the **parcel creation and confirmation process**.  
- Creating the **“My Parcels” section** with real-time delivery status.  
- Ensuring a **smooth user experience** and clean UI design.  
- Integrating with the **company’s delivery API** for live updates and tracking.

---

## 📸 Screenshots
*(You can add screenshots in a `/screenshots` folder)*

| Home | Create Parcel | Package Details | Confirmation | My Parcels |
|------|----------------|----------------|---------------|-------------|
| ![Home](screenshots/home.png) | ![Create Parcel](screenshots/create_parcel.png) | ![Package Details](screenshots/package_details.png) | ![Confirmation](screenshots/confirmation.png) | ![My Parcels](screenshots/my_parcels.png) |

---

⭐ *If you found this project interesting, consider giving it a star on GitHub!*
