# 🎒 SmartBag
**Know Where Your Child Is. Anytime. Anywhere.**

> A modern SaaS-style platform for an IoT-based child safety and smart tracking system.

![SmartBag UI Preview](https://via.placeholder.com/1200x600/0F172A/FFFFFF?text=SmartBag+Dashboard+Preview)

## 🌟 Overview

SmartBag is the frontend application for a complete IoT hardware-software ecosystem. Designed to pair with a physical ESP32 and GPS module placed inside a child's school bag, this dashboard allows parents to monitor their child's journey, receive instant alerts, and ensure safety through a premium, production-grade interface.

## ✨ Features

- **📍 Live Tracking:** Real-time GPS location updates with visual route mapping.
- **🛡️ Safe Zones (Geofencing):** Define virtual boundaries (Home, School) and get alerts on entry/exit.
- **🚨 SOS Emergency Mode:** Instantly flashes alerts and provides quick access to emergency contacts and navigation.
- **📊 Analytics & Health:** AI-driven route anomaly detection, travel time metrics, and deep device health diagnostics (battery, GSM signal).
- **🌙 Modern Design:** Fully responsive, mobile-first UI with a dark mode glassmorphism aesthetic inspired by modern startups.

## 💻 Tech Stack

- **Framework:** [Next.js 14](https://nextjs.org/) (App Router)
- **Styling:** [TailwindCSS](https://tailwindcss.com/)
- **Animations:** [Framer Motion](https://www.framer.com/motion/)
- **Maps:** [Leaflet](https://leafletjs.com/) & [React-Leaflet](https://react-leaflet.js.org/)
- **Charts:** [Recharts](https://recharts.org/)
- **Icons:** [Lucide React](https://lucide.dev/)

## 🚀 Getting Started

### Prerequisites
Make sure you have Node.js (v18 or higher) installed on your system.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/akshar-28-04/Smart_Bag.git
   cd Smart_Bag
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run the development server:
   ```bash
   npm run dev
   ```

4. Open [http://localhost:3000](http://localhost:3000) with your browser to see the application.

## 🔌 Hardware Integration (Coming Soon)
The SmartBag frontend is designed to consume webhooks and REST APIs from an ESP32 backend. The hardware stack utilizes:
- ESP32 Microcontroller
- Neo-6M GPS Module
- SIM800L / GSM Module for cloud connectivity
- Battery Management System (BMS)

*(Note: The current repository contains the React frontend populated with high-fidelity demo data for presentation purposes).*

## 📄 License
This project is licensed under the MIT License.
