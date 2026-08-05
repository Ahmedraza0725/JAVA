# 🌱 Plant Care System (Java Swing Desktop Application)

![Java](https://img.shields.io/badge/Language-Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![GUI Framework](https://img.shields.io/badge/Framework-Java_Swing-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

## 📌 Project Overview
**Plant Care System** ek desktop-based graphical user interface (GUI) application hai jise **Java Swing** aur **AWT** libraries ka use kar ke banaya gaya hai. Iska maqsad users ko apne plants ki details, water frequency, health status, aur fertilizer requirements ko ek hi organized table aur dashboard par manage karne mein madad dena hai.

---

## ✨ Key Features & Functionality
- **Interactive Dashboard Table:** Ek clean `JTable` layout jo saare added plants ki list aur details (`Name`, `Type`, `Water Frequency`, `Health`, `Fertilizer`) show karta hai.
- **Add New Plant:** Ek dedicated dialog box jiske zariye aap naye plant ki information enter kar ke list mein add kar sakte hain.
- **Search Plant:** Plant ke naam se search karne ki sahoolat, jisse specific plant ki details popup message mein show ho jati hain.
- **Plant Summary Report:** Automatic calculation jo total plants, healthy plants, aur unhealthy plants ko unke health score ke mutabiq count kar ke display karti hai.
- **Delete Plant Record:** Kisi bhi plant ko uske naam ke zariye database/list se remove karne ka option.

---

## 🛠️ Tech Stack & Requirements
- **Language:** Java (JDK 8 ya is se above)
- **GUI Framework:** Java Swing (`javax.swing`) & AWT (`java.awt`)
- **IDE:** IntelliJ IDEA, Eclipse, ya NetBeans

---

## 📂 Code Architecture
Application do main components par mushtamil hai:
1. **`PlantCareSystem` (Main Class):** UI components, windows (`JFrame`, `JDialog`), tables, aur buttons ke event listeners ko handle karti hai.
2. **`Plant` (Data Model Class):** Plant object ke attributes (`name`, `type`, `waterFrequency`, `health`, `fertilizer`) ko manage karti hai.

---

## 🚀 How to Run the Application

Apne local system par is project ko run karne ke liye in steps ko follow karein:

**1. Clone the repository:**
```bash
git clone [https://github.com/Ahmedraza0725/JAVA.git](https://github.com/Ahmedraza0725/JAVA.git)
