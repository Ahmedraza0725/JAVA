<div align="center">

### 🌱 Plant Care System
**Java Swing Desktop Application — Plant Care & Management Dashboard**  
Real-time plant registration, dynamic data table tracking, health status analysis, watering frequency scheduling, and summary reports — all in a sleek GUI desktop app.

</div>

---

## 📖 About
**Plant Care System** is an interactive desktop application built to help users seamlessly manage and monitor their indoor and outdoor plants. Beyond a basic list view, it calculates health metrics, categorizes plants by their overall condition, tracks watering frequencies in days, and stores critical plant care data locally.

This tool is designed for personal gardening tracking, plant care automation awareness, and lightweight desktop management. It performs all operations locally using Java collections with zero external database dependencies.

---

## ✨ Features

| Category | Details |
| :--- | :--- |
| 📊 **Interactive Plant Table** | Dynamic `JTable` using `DefaultTableModel` displaying comprehensive rows of all added plants |
| ➕ **Add Plant Dialog** | Modal form window (`JDialog`) supporting custom plant parameters with error handling and frequency validation |
| 🔎 **Plant Search Utility** | Instant lookup system to search individual plants by name and view complete record details |
| 📈 **Automated Health Summary** | Smart calculation module categorizing total, healthy (50–100 score), and unhealthy plants (<50 score) |
| 🗑️ **Record Deletion** | Safe removal mechanism to purge obsolete or deleted plant entries from the active list |
| 🖥️ **Custom Swing UI** | Polished layout using custom color themes, buttons, and scroll panes for smooth navigation |

---

## 🖼️ Preview
```text
┌──────────────────────────────────────────────────────────┐
│  Plant Care System                                       │
├──────────────────────────────────────────────────────────┤
│  [Name]       [Type]      [Water Freq]  [Health]  [Fert.]│
│  Fern         Indoor      3 Days        85        Balanced │
│  Cactus       Succulent   10 Days       40        Low-Nit. │
│                                                          │
│  [ Add Plant ]  [ Search Plant ]  [ Summary ]  [ Delete ]│
└──────────────────────────────────────────────────────────┘

```

---

## 🧰 Requirements & Tech Stack

* **Language:** Java (JDK 8 or higher)
* **GUI Framework:** Java Swing (`javax.swing`) & AWT (`java.awt`)
* **Data Structures:** Java Collections Framework (`ArrayList`, `DefaultTableModel`)
* **IDE:** Compatible with IntelliJ IDEA, Eclipse, or NetBeans

---

## 🚀 Installation & Usage

### 1. Clone the repository

```bash
git clone [https://github.com/Ahmedraza0725/JAVA.git](https://github.com/Ahmedraza0725/JAVA.git)
cd JAVA

```

### 2. Compile and Run

```bash
javac PlantCareSystem.java
java PlantCareSystem

```

### Quick Start Guide

* **Add a Plant:** Click the **Add Plant** button, enter the plant's name, type, water frequency, health score, and fertilizer details, then save.
* **Search Plant:** Click **Search Plant** and type the name to view its complete specifications instantly.
* **View Summary:** Click **Show Plant Summary** to view an automated breakdown of your garden's health status.
* **Delete Plant:** Click **Delete Plant** and provide the target plant name to clear its record.

---

## 📁 Project Structure

```text
JAVA/
├── PlantCareSystem.java      # Main entry point, GUI frames, dialog managers, and Plant model class
├── README.md                 # Comprehensive project documentation
└── LICENSE                   # MIT Open Source License

```

---

## 🏗️ Architecture & Core Components

| Class / Component | Responsibility |
| --- | --- |
| `PlantCareSystem` | Initializes main GUI layout (`JFrame`), scroll panes, buttons, and event listeners |
| `openAddPlantDialog()` | Manages input dialog forms (`JDialog`) and validates user entries |
| `searchPlantDialog()` | Handles searching logic across the `ArrayList` collection |
| `showPlantSummary()` | Computes health metrics and displays analytical status boxes |
| `deletePlantDialog()` | Handles removal workflow and updates table models dynamically |
| `Plant` (Model) | Object blueprint encapsulating name, type, frequency, health, and fertilizer fields |

---

## 🗺️ Roadmap

* [ ] Implement file persistence (save/load plant data to JSON or text files)
* [ ] Add automated watering reminder alerts based on frequency days
* [ ] Introduce search filtering and sorting options by health status
* [ ] Dark/Light theme toggle switch

---

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

---

Built with 💻 and ☕ by [Muhammad Ahmed Raza](https://www.google.com/search?q=https://github.com/Ahmedraza0725)