# 🧠 Semantic Segmentation in AR (Unity + Niantic Lightship)
---

## 📽️ Demo



---

## 🔍 Overview

This project demonstrates how to apply **semantic segmentation** in an AR experience using **Niantic Lightship ARDK** and **Unity**. The app classifies real-world surfaces like sky, ground, trees, and buildings and uses that information to influence AR interactions.

🧩 Semantic segmentation allows the AR system to:
- Detect where AR objects *should* and *should not* be placed.
- Interact differently with real-world surfaces (e.g., only walk on roads or only place effects on grass).
- Visualize environmental understanding in real time.

---

## 🛠️ Technologies Used

- **Unity3D** (C#)
- **Niantic Lightship ARDK**
- **Shader Graph**
- **Semantic Segmentation Channel API**
- **Mobile (iOS / Android)**

---

## 🎯 Features

✅ Real-time **semantic texture** generation from AR camera  
✅ Visualization of detected channels (e.g., sky, building, ground, tree, etc.)  
✅ **Custom shaders** to map textures in AR space  
✅ Dynamic AR behavior based on segmented surfaces  
✅ Matrix transformation to align camera and semantic data  
✅ Optimized for mobile AR performance

---

## 🚀 Getting Started

### Prerequisites

- Unity 3D (with Android/iOS build support)
- Niantic Lightship ARDK (get it from [Lightship.dev](https://lightship.dev/))
- AR-capable device (ARKit for iOS or ARCore for Android)

### Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/iamashkan/Semantic-Segmentation-using-Unity-and-Niantic-Lightship.git

