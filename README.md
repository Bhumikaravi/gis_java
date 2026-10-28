<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=064E3B,047857,10B981&height=220&section=header&text=Guitar%20Inventory%20System%20%28Java%20OOP%29&fontSize=38&fontColor=ffffff&fontAlignY=38&desc=Encapsulated%20Inventory%20Search%20Engine%20and%20UML%20Object%20Architecture&descSize=16&descAlignY=62&descAlign=50" width="100%" alt="Guitar Inventory System (Java OOP) Header Banner"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Language-Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"/> <img src="https://img.shields.io/badge/Paradigm-Object--Oriented%20Programming-blue?style=for-the-badge" alt="OOP"/> <img src="https://img.shields.io/badge/Design-UML%20Architectural%20Modeling-orange?style=for-the-badge" alt="UML"/>
</p>


## 📌 Table of Contents
- [📖 Executive Summary](#-executive-summary)
- [✨ Key Features & Capabilities](#-key-features--capabilities)
- [🏗️ System Architecture & Workflow](#️-system-architecture--workflow)
- [🛠️ Tech Stack Breakdown](#️-tech-stack-breakdown)
- [⚙️ Reproducible Quickstart & Setup](#️-reproducible-quickstart--setup)
- [📂 Project Directory Layout](#-project-directory-layout)
- [👩‍💻 Author & Contributions](#-author--contributions)

---

## 📖 Executive Summary
### Problem Statement
Retail musical instrument businesses require flexible, decoupled inventory search mechanisms that shield instrument specifications while supporting dynamic attribute filtering.

### Motivation & Solution Overview
An Object-Oriented Java desktop application modeling musical instruments, inventory catalogs, and decoupled search algorithms using fundamental software engineering principles.

---

## ✨ Key Features & Capabilities
- **Strict Encapsulation:** Shields serial numbers, builder types, model names, wood specs, and pricing.
- **Decoupled Search Logic:** Search queries match client preferences without hardcoding instrument classes.
- **Architectural Documentation:** Includes structural object-level UML diagram (`object level diagram.jpg`).

---

## 🏗️ System Architecture & Workflow
```mermaid
classDiagram
    class Guitar {
        -String serialNumber
        -double price
        -String builder
        -String model
        -String type
        -String backWood
        -String topWood
        +getSerialNumber()
        +getPrice()
        +getBuilder()
        +getModel()
    }
    class GuitarinventorySystem {
        -List~Guitar~ guitars
        +addGuitar(...)
        +getGuitar(serialNumber)
        +search(spec)
    }
    class Main {
        +main(args)
    }
    GuitarinventorySystem "1" *-- "*" Guitar
    Main ..> GuitarinventorySystem
```

---

## 🛠️ Tech Stack Breakdown
| Category | Technologies |
|---|---|
| **Language** | Java (JDK 8+) |
| **Design Paradigm** | Object-Oriented Programming (OOP) |
| **Modeling** | UML Object-Level Architectural Diagram |

---

## ⚙️ Reproducible Quickstart & Setup
### Compilation and Run
```bash
# 1. Clone repository
git clone https://github.com/Bhumikaravi/gis_java.git
cd gis_java

# 2. Compile Java source files
javac *.java

# 3. Execute Main entry point
java Main
```

---

## 📂 Project Directory Layout
```text
gis_java/
├── Guitar.java                  # Instrument entity class
├── GuitarinventorySystem.java   # Inventory catalog management & search engine
├── Main.java                    # Entry point & execution driver
├── object level diagram.jpg     # Object-level UML diagram
└── README.md
```

---

## 👩‍💻 Author & Contributions
Developed by **Bhumika Ravi** ([@Bhumikaravi](https://github.com/Bhumikaravi)), Bachelor of Computer Applications (BCA) at **Alliance University, Bengaluru**.

- 💻 **GitHub Profile:** [github.com/Bhumikaravi](https://github.com/Bhumikaravi)
- 🔗 **LinkedIn:** [linkedin.com/in/bhumika-ravi-b5a01b326](https://www.linkedin.com/in/bhumika-ravi-b5a01b326/)
- 📬 **Email Contact:** [bhumikaravi2006@gmail.com](mailto:bhumikaravi2006@gmail.com)

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=064E3B,047857,10B981&height=100&section=footer" width="100%" alt="Footer Banner"/>
</p>
