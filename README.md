# **Smart Health Monitoring System (Prototype)** 🏆 **Best Project Award Winner**

A modern, cross-platform solution for **real-time health tracking** using **wearable BLE sensors**, a **Flutter patient app**, and a **React-based doctor dashboard**.
The system streams live health metrics, visualizes historical data, and supports better medical decision-making.

---

## **💡 The Problem & Our Solution**

Imagine an elderly patient who needs to regularly check their heart rate, oxygen levels, and blood pressure.
Traditionally, this means **frequent hospital visits** — taking time, money, and energy, especially for those in rural or hard-to-reach areas.

Now imagine if **their vital signs were monitored from home**, in real time, and doctors could instantly see their condition without a single trip to the clinic.

That’s exactly what the **Smart Health Monitoring System** does.
By combining **IoT wearable devices**, **mobile apps**, and a **doctor’s web dashboard**, it allows patients to:

* Track their health continuously from home
* Get immediate feedback from their doctor
* Reduce unnecessary hospital visits
* Detect early warning signs before emergencies

---

## **📌 Overview**

The **Smart Health Monitoring System** enables continuous monitoring of vital signs for patients while providing doctors with powerful visualization and communication tools.

**Core Components:**

1. **Patient App (Flutter)** – Displays live and past health metrics with a sleek, glassmorphic UI.
2. **Doctor Dashboard (React)** – Offers interactive charts, AI-assisted queries, and patient communication.
3. **Wearable BLE Hardware** – Streams vital signs in JSON format, updated every second.

---

## **📱 Patient Mobile App**

* 🔗 **Instant BLE device connection** with backend sync (<3s delay)
* 📊 Live 24-hour stream + weekly/monthly history charts
* ⚖️ BMI Calculator, Sleep Summary, Step Count *(prototype)*
* 💡 Smart health insights & interpretations
* 👤 Profile management & device status display

---

## **💻 Doctor Web Dashboard**

* 🔍 Search & view patient profiles with full medical history
* 📈 Visualize vitals via line charts, ECG graphs, and combined metrics
* 🤖 AI Assistant for natural-language health data queries
* ✉️ Messaging & notifications for patient engagement
* 🌙 Light/Dark mode & fully responsive UI

---

## **⌚ Wearable Hardware**

* BLE sensors measuring **Heart Rate, SpO₂, Temperature, Blood Pressure**
* Data streamed as JSON at **1 reading per second**
* Seamless mobile + backend integration

---

## **🛠 Tech Stack**

| Layer              | Technologies                                                                     |
| ------------------ | -------------------------------------------------------------------------------- |
| Mobile App         | Flutter (Dart), `flutter_reactive_ble`, `fl_chart`, Google Fonts                 |
| Web Dashboard      | React v18 + TypeScript, Vite, Tailwind CSS, shadcn-ui, react-chartjs-2, Recharts |
| Networking & State | Flutter Stateful Widgets, React Context API, HTTP/Custom API                     |
| Backend            | Node.js or Django REST API                                                       |
| Auth               | JWT / Firebase (configurable)                                                    |
| Hardware           | BLE Sensors (JSON streaming)                                                     |

---

## **🔗 System Architecture**

```
[Wearable Device]
       ↓ BLE (JSON)
[Flutter Mobile App]
       ↓ REST API
[React Doctor Dashboard]
```

---

## **📂 Repositories**

* **Main Landing Page (this repo)**
* **Patient App :** \[https://github.com/poricf/smart_health_app]
* **Doctor Dashboard:** \[https://github.com/kika1s1/patient-health-monitoring-system]

---

## **🚀 Installation**

### **Mobile App (Flutter)**

```bash
flutter pub get
flutter run
# Configure BLE device & backend in bluetooth_service.dart & api_service.dart
```

### **Web Dashboard (React)**

```bash
cd client
npm install
npm run dev
# Open http://localhost:5173
```

---

## **🖼 Screenshots**

**Patient App**
![Home](images/flutter_home.png)
![Charts](images/flutter_stats.png)
![Profile](images/flutter_profile.png)

**Doctor Dashboard**
![Patients](images/web_patient_list.png)
![Metrics](images/web_metrics.png)
![AI & Notifications](images/web_ai_notifications.png)

---

## **📅 Future Enhancements**

* Native step counter support
* Full sleep tracking integration
* Firebase authentication
* Push notification system
* Advanced analytics for doctors

---

## **👥 Designed For**

* **Doctors** – Data visualization, patient insights, and AI-assisted queries
* **Patients** – Continuous, accessible health monitoring
* **Healthcare Systems** – Real-time and historical health data management

---

> 🏆 **Award:** Recognized as *Best Project* for innovation, cross-disciplinary collaboration, and real-world healthcare impact.

