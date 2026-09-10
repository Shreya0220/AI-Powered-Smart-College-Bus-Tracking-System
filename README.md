# AI-Powered Smart College Bus Tracking System

## 📌 Project Overview

The AI-Powered Smart College Bus Tracking System is a smart transportation platform designed to help colleges manage and monitor their bus transportation services efficiently.

The system provides real-time bus tracking, route information, estimated arrival time, transport fee status, attendance verification, notifications, and dashboards for different users.

## ✨ Key Features

- 🚌 Real-time college bus tracking
- 📍 Live GPS-based bus location
- 🤖 AI-powered ETA prediction
- 🚦 Traffic and delay prediction
- 🗺️ Route and stop information
- 📱 Student transportation dashboard
- 👨‍👩‍👧 Guardian transportation monitoring
- 👨‍🏫 Faculty transportation access
- 🛡️ Admin transportation management
- 💳 Transport fee status from College ERP
- 📷 QR-based bus boarding attendance
- 🔔 Bus arrival, departure, delay and transport notifications
- 🔄 Real-time bus replacement updates
- 📡 GPS offline-data synchronization
- 🧭 Geofencing for trip and attendance verification

## 👥 User Roles

### 🎓 Student

- View assigned bus and route information
- Track buses in real time
- View estimated arrival time
- Check transport fee status
- View boarding/attendance status
- View driver and conductor contact details
- Receive transportation notifications

### 👨‍👩‍👧 Guardian

- Monitor student's bus transportation
- View bus location and ETA
- Receive important bus and arrival notifications

### 👨‍🏫 Faculty

- View available college buses
- Track active buses and routes
- Receive transportation updates

### 🛡️ Admin

- Manage buses and routes
- Manage drivers and conductors
- Monitor active and completed trips
- Monitor bus locations and statuses
- Manage student transport information
- Receive alerts for unauthorized/inactive transport access
- Manage bus replacements and transportation operations

> **Note:** Drivers and conductors are managed by the Admin. There is no separate Driver Login or Driver Dashboard.

## 🤖 AI & Smart Features

The system includes AI-based and intelligent transportation features to improve bus tracking and travel planning.

- 🤖 AI-powered Estimated Time of Arrival (ETA)
- 🚦 Traffic-aware ETA prediction
- 🌦️ Weather-aware ETA adjustment
- 📊 Delay prediction based on traffic, weather and bus speed
- 📍 GPS-based real-time location updates
- 🧭 Geofencing for trip and attendance verification
- 🔄 Automatic trip start and trip completion detection
- 📡 Offline GPS data storage and synchronization
- 🔔 Intelligent transportation alerts and notifications

## 🚌 Transportation & Bus Management

The system supports smart college transportation management including:

- Bus registration and management
- Route and stop management
- Driver and conductor information
- Bus assignment and replacement
- Live bus status monitoring
- Automatic trip start detection
- Automatic trip completion detection
- College arrival and departure tracking
- GPS connectivity monitoring

The Admin Dashboard can monitor buses that are:

- 🟢 Running / In Transit
- 🟡 Delayed
- 🔵 Arrived
- ⚫ Offline
- 🔴 Maintenance
- ⏹️ Trip Ended

## 📷 QR-Based Boarding Attendance

The system supports QR-based bus boarding verification.

The attendance process includes:

1. Student logs into the system.
2. Student scans the bus QR code.
3. Student transport fee status is verified.
4. GPS/geofence location is verified.
5. QR validity and time restrictions are checked.
6. Boarding attendance is recorded.
7. The actual bus used by the student is stored.

Students with an active transport fee can use any authorized college bus. The bus used during actual boarding is recorded for attendance.

## 💳 Transport Fee & College ERP

Transport fee information is intended to be synchronized with the College ERP system.

Possible transport statuses include:

- PAID / ACTIVE
- NOT PAID
- PENDING
- EXPIRED

If a student without an active transport fee attempts to access transportation services, the system can generate an alert for the Admin.

## 🔔 Notifications & Alerts

The system provides transportation-related notifications such as:

- Bus departure notification
- Bus arrival notification
- Delay notification
- College arrival notification
- Bus replacement notification
- GPS/offline status notification
- Unauthorized transport access alert

## 🔄 Real-Time Bus Replacement

If the Admin changes or replaces a bus, the updated information can be propagated to connected users in real time.

For example:

`BUS-05 → BUS-12`

The updated bus number, route, driver, conductor, location and ETA can be reflected without requiring a manual page refresh.

## 🛠️ Technology Stack

### Frontend

- React.js
- Vite
- HTML5
- CSS3
- JavaScript

### Backend

- Node.js
- Express.js

### Database

- MongoDB

### Real-Time Communication

- Socket.IO / WebSocket

### AI & Data Processing

- AI-based ETA prediction
- Traffic and weather factors
- GPS simulation and location processing

### Development Tools

- Visual Studio Code
- Git
- GitHub

## 📂 Project Structure

```text
AI-Powered-Smart-College-Bus-Tracking-System/
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── pages/
│   │   │   ├── admin/
│   │   │   ├── student/
│   │   │   ├── guardian/
│   │   │   └── faculty/
│   │   ├── data/
│   │   ├── context/
│   │   ├── services/
│   │   └── utils/
│   │
│   ├── package.json
│   └── vite.config.js
│
└── README.md