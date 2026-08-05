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
