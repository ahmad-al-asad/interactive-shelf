# 🛒 Immersive Virtual Shelf: An Interactive XR Experience for Nutritional Awareness

**Developed by:**  
**Ahmad Al Asad** — MSc. Student, Department of Computer Science, University of Calgary  
**Tarif Ashraf** — MSc. Student, Department of Computer Science, University of Calgary  

🎮 **Engine:** Unreal Engine 5  
💻 **Platform:** Meta Quest Pro (VR)  

---

## 🧩 Overview

**Immersive Virtual Shelf** is a **Virtual Reality (VR)** application that creates an **interactive shopping experience** for users to explore and learn about nutritional information of various food items in a virtual environment.  
The project combines **educational engagement** with **immersive XR technology** to promote nutritional awareness among users.

---

## 🎯 Motivation

Modern consumers often lack engaging and interactive ways to learn about the **nutritional content** of their food.  
This project addresses that gap by utilizing **Extended Reality (XR)** as a medium for **experiential learning**, helping users visualize and understand health information in a hands-on, immersive manner.

**Target Users:**
- Health-conscious consumers  
- Educators and students  
- Retail and e-commerce sectors  

---

## ⚙️ Core Idea & Implementation

### 🧠 Concept
Users enter a **virtual store environment**, where they can:
- **Grab, move, rotate, and throw** objects using VR controllers.  
- **Access an augmented info panel** to view **nutritional data** (calories, sugar, carbs, etc.).  
- **Interact naturally** through gestures and controller inputs.

### 🏗️ Technical Details
- **Engine:** Unreal Engine 5 (VR Template)  
- **Interaction Mechanism:** Blueprint scripting, Line Trace, and Widget Binding  
- **Data Source:** [Kaggle – Food Nutrition Information Dataset](https://www.kaggle.com/datasets/lazycoder00/-nutritionalfacts-fruit-vegetables-seafood)  
- **Controllers:**  
  - *Right-hand controller* — Grabbing and manipulating items  
  - *Left-hand controller* — Triggering nutritional info widgets  

---

## 🧑‍💻 Features

✅ Interactive 3D shelves with fruits and vegetables  
✅ Real-time nutritional information display  
✅ Physics-based object interaction  
✅ Dynamic user interface (UMG Widget System)  
✅ Immersive environment with spatial feedback  

---

## 🧪 User Testing & Feedback

Users appreciated the **clarity of environment** and **realistic shelf interaction**, but noted:
- Line tracing was too long and confusing.  
- Font colors sometimes blended with the background.  
- Positive comments on usability, visual clarity, and educational potential.

> *“People are more health-conscious, and this app helps visualize nutritional data intuitively.”*  
> — User feedback session

---

## 💡 Potential Applications

| Domain | Use Case |
|---------|-----------|
| **Retail & E-Commerce** | Virtual shopping with interactive product insights |
| **Education & Research** | Teaching nutrition concepts through immersive visualization |
| **Healthcare & Wellness** | Assisting diet planning for patients and fitness users |

---

## 🚀 Future Work

🔹 Dynamic data loading from external CSV/database  
🔹 Hand gesture and voice recognition support  
🔹 Expansion to diverse food categories  
🔹 Enhanced realism with AI-driven recommendations  

---

## 🧭 Repository Structure

interactive-shelf/
├── Assets/                 # 3D models, textures, and environment assets
├── Blueprints/             # Core VR logic and interactions
├── Widgets/                # UI widgets for nutritional info display
├── Config/                 # Unreal Engine configuration files
├── README.md               # Project documentation
└── .uproject               # Unreal Engine project file

---

## 🛠️ Requirements

- **Unreal Engine 5.3+**  
- **Meta Quest Pro or compatible VR headset**  
- **Windows 10/11** (VR-ready PC)  
- **Kaggle Dataset Import (CSV)** for nutritional data  

---


“Immersive learning begins when interaction meets awareness.” 🌱

