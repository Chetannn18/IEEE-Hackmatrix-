# 🚨 Trackmate – Smart Safety & Location Intelligence Platform

> **HackMatrix 2K26 | IEEE Computer Society SBC, MITS Gwalior**

## 📌 Project Title

**Trackmate – Smart Safety & Location Intelligence Platform**

Trackmate is a smart safety and location-based platform designed to help users stay safe, quickly report emergencies, and enable authorities to monitor and respond to incidents efficiently.

---

## 👥 Team

**Team Name:** Trackmate

### Team Members

* **Chetan Nagre** – Frontend Development & UI/UX
* **Naitik Jain** – Backend Development, Geofencing & System Integration
* **Dewarsh Jain** – Frontend Development & UI/UX
* **Jayshree Rathore** – AI & Blockchain

---

## 🎯 Problem Statement

In many real-world environments such as campuses, public spaces, and large institutions, people may face safety risks without having an efficient way to communicate emergencies or receive location-aware safety information.

Traditional emergency systems often lack:

* Real-time location awareness
* Quick emergency reporting
* Location-based safety information
* Centralized monitoring for authorities
* Clear identification of safe and restricted zones
* Efficient communication between users and authorities

There is a need for an integrated platform that combines **location intelligence, emergency response, geofencing, and centralized monitoring** into a single system.

---

## 💡 Solution Overview

**Trackmate** provides a smart safety ecosystem that connects users with authorities through real-time location-based services.

The platform includes an emergency **SOS mechanism**, location-aware safety zones, and an authority dashboard for monitoring incidents.

### 🔑 Key Features

* 🚨 **SOS Emergency Button**

  * Allows users to quickly trigger an emergency alert.
  * Shares relevant location information with the concerned system.

* 📍 **Location Tracking**

  * Uses location information to provide context-aware safety services.

* 🗺️ **Safety Zones**

  * Areas can be classified into:

    * 🟢 Safe
    * 🟡 Moderate
    * 🔴 Restricted

* 🚧 **Geofencing**

  * Helps identify when users enter or leave predefined geographical zones.

* 👮 **Authority Dashboard**

  * Provides authorities with a centralized view of safety-related incidents.

* 📊 **Real-Time Monitoring**

  * Enables monitoring of emergency events and user activity.

* 🔐 **Secure System Architecture**

  * Designed with security and controlled access in mind.

* 🤖 **AI Integration**

  * AI-based components can assist with intelligent analysis and decision support.

* ⛓️ **Blockchain Integration**

  * Blockchain technology is incorporated where appropriate to improve trust, integrity, and transparency of relevant records.

---

## 🏗️ System Architecture

The project follows a modular architecture consisting of:

```text
                    ┌─────────────────────┐
                    │       User          │
                    │   Web / Mobile App  │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │    Frontend Layer   │
                    │  UI / Maps / SOS    │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │    Backend / APIs   │
                    │ Authentication      │
                    │ Business Logic      │
                    └──────────┬──────────┘
                               │
              ┌────────────────┼────────────────┐
              ▼                ▼                ▼
       ┌─────────────┐  ┌─────────────┐  ┌─────────────┐
       │ Geofencing  │  │ AI Services │  │ Blockchain  │
       └─────────────┘  └─────────────┘  └─────────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │ Authority Dashboard │
                    └─────────────────────┘
```

---

## 🛠️ Technology Stack

### Frontend

* React
* TypeScript
* Vite
* Tailwind CSS
* HTML5
* CSS3
* JavaScript

### Backend

* Node.js
* Express.js
* REST APIs

### Database

* MongoDB
* Prisma ORM
* Redis

### Mobile Application

* Flutter
* Dart

### AI / Computer Vision

* Python
* Machine Learning
* AI-based analysis

### Blockchain

* Blockchain-based components for secure and verifiable data handling

### Development Tools

* Git
* GitHub
* VS Code
* Postman

---

## 📂 Project Structure

```text
Trackmate/
│
├── Tackmate_Frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── context/
│   │   ├── hooks/
│   │   ├── pages/
│   │   ├── lib/
│   │   ├── types/
│   │   └── App.tsx
│   ├── package.json
│   └── vite.config.ts
│
├── Trackmate_Backend/
│
├── Trackmate_Contracts/
│
├── Trackmate_app/
│
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

Make sure the following are installed:

* Node.js
* npm
* Git
* MongoDB
* Flutter SDK (for mobile application)
* Python (for AI-related modules)

---

## 💻 Frontend Setup

Clone the repository:

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
```

Navigate to the frontend:

```bash
cd Tackmate_Frontend
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

The application will be available on the local development server shown in the terminal.

---

## ⚙️ Backend Setup

Navigate to the backend directory:

```bash
cd Trackmate_Backend
```

Install dependencies:

```bash
npm install
```

Create the required environment configuration:

```text
.env
```

Add the required database and application configuration.

Then start the backend:

```bash
npm run dev
```

> Environment variables and secret keys should **never be committed** to the repository.

---

## 📱 Mobile Application Setup

Navigate to the Flutter application:

```bash
cd Trackmate_app
```

Install dependencies:

```bash
flutter pub get
```

Run the application:

```bash
flutter run
```

---

## 🔗 Live Demonstration

🌐 **Live Demo:** `<ADD_LIVE_DEMO_LINK>`

🎥 **Demo Video:** `<ADD_DEMO_VIDEO_LINK>`

> Replace these placeholders with the actual deployment/demo links before final submission.

---

## 📸 Screenshots

Add screenshots of the major features here.

### User Interface

`<ADD_SCREENSHOT>`

### SOS / Emergency System

`<ADD_SCREENSHOT>`

### Authority Dashboard

`<ADD_SCREENSHOT>`

### Safety Zones / Map

`<ADD_SCREENSHOT>`

---

## 🔐 Environment Variables

For security reasons, sensitive credentials must not be committed to GitHub.

Example:

```env
DATABASE_URL=
JWT_SECRET=
API_KEY=
MONGODB_URI=
REDIS_URL=
```

Create your own `.env` file locally and configure the required variables.

---

## 🧪 Testing

The project includes testing infrastructure for validating application functionality.

Frontend tests can be executed using the configured testing tools:

```bash
npm test
```

End-to-end tests can be executed using:

```bash
npx playwright test
```

---

## 📈 Future Scope

Future improvements for Trackmate may include:

* Advanced AI-based risk prediction
* More accurate real-time location intelligence
* Automated emergency response workflows
* Advanced analytics for authorities
* IoT-based safety sensors
* Improved offline functionality
* Integration with institutional emergency services
* Advanced blockchain-based verification
* Multi-institution deployment

---

## 🌟 Why Trackmate?

Trackmate aims to move safety systems from **reactive emergency handling** toward **proactive, location-aware safety management**.

By combining:

**📍 Location Intelligence + 🚨 Emergency Response + 🗺️ Geofencing + 🤖 AI + ⛓️ Blockchain**

Trackmate provides a unified platform for improving safety and coordination between users and authorities.

---

## 👨‍💻 Team Hackathon Submission

**HackMatrix 2K26**

Organized by:

**IEEE Computer Society SBC, MITS Gwalior**

---

## 📄 License

This project was developed as part of **HackMatrix 2K26**.

© 2026 Trackmate Team. All rights reserved.
