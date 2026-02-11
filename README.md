# ⚡ TNEB Analyzer – Smart Watt Meter & Electricity Bill Estimator

TNEB Analyzer (WATT Meter) is a smart web-based electricity consumption and bill estimation system built using **Tamil Nadu Electricity Board (TNEB) slab rates**.  
It allows users to add household devices, track energy usage, and calculate accurate monthly and yearly electricity bills with visual analytics.

---

## 🚀 Key Features

### 🔐 Authentication
- Email & Password login
- Google Sign-In
- Password reset
- Secure authentication using **Firebase Auth**

---

### ⚙️ Device Management
- Add electrical devices with:
  - Device name
  - Power (Watts)
  - Daily usage (Hours)
- Edit & delete devices
- Predefined common devices with auto wattage fill
- All data saved per user using **Firebase Realtime Database**

---

### 📊 Consumption Analysis
- Daily, Monthly & Yearly energy usage (kWh)
- Total monthly units calculation
- TNEB slab-wise bill calculation
- Billing breakdown by slab
- Consumption level indicator:
  - Low
  - Moderate
  - High

---

### 📈 Visual Analytics
- Pie chart showing device-wise energy consumption
- Animated consumption meter
- Slab-wise cost breakdown
- Energy-saving tips shown dynamically

---

### 💡 Energy Saving Tips
- Random smart tips displayed after calculation
- Helps users reduce electricity usage and bill amount

---

## 🧠 TNEB Slab Rates Used (Domestic – 2023)
- First 100 units – Free
- Next 100 units – ₹2.25/unit
- Next 200 units – ₹4.50/unit
- Next 100 units – ₹6.00/unit
- Next 100 units – ₹8.00/unit
- Next 400 units – ₹9.00/unit
- Remaining units – ₹10.00/unit

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **UI Framework:** Bootstrap 5
- **Animations:** Animate.css
- **Icons:** Font Awesome, Bootstrap Icons
- **Charts:** Chart.js
- **Backend:** Firebase
  - Authentication
  - Realtime Database
- **Hosting:** Firebase Hosting

---

## 📱 Responsive Design
- Mobile-friendly UI
- Bottom navigation for easy access
- Optimized for smartphones and desktops

---


---

## 🌱 Future Enhancements
- Monthly bill history
- PDF bill report download
- Appliance usage suggestions
- Dark / light mode toggle
- Admin dashboard for analytics
- Multi-language support (Tamil / English)

---

## 👨‍💻 Developed By
**Sakthivel**  
Department of Information Technology  
PKN College of Arts & Science

---

## 📜 Disclaimer
This project is developed for **educational purposes only**.  
Actual electricity bills may vary based on official TNEB charges, subsidies, and policy updates.
