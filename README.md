# 🧠 Semantic Segmentation in AR (Unity + Niantic Lightship)

> A real-time Augmented Reality experience powered by Semantic Segmentation to make AR environment-aware and smarter.  
> Built with Unity3D and Niantic's Lightship ARDK.
---

## 📽️ Demo



---

> [!NOTE]
> **Built in 2024 on Lightship ARDK 3.x, which Niantic has since retired.**
> `lightship.dev` was decommissioned on **27 February 2026**, ARDK 3.x is deprecated, and
> Shared AR stopped functioning on **1 May 2026**. The platform moved to
> [Niantic Spatial NSDK 4.0](https://www.nianticspatial.com/docs/nsdk/migration_guide/),
> which still provides scene segmentation, depth, occlusion, meshing and VPS across Unity,
> Swift and Kotlin — critical fixes for 3.x run only until 28 February 2027.
>
> This repository is kept as-is for the shader and segmentation-channel work, which is the
> part worth reading. It will not build against a current SDK without migrating to NSDK 4.0.

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
- Niantic Lightship ARDK — **this link is dead**: `lightship.dev` was decommissioned in
  February 2026. The current SDK is [Niantic Spatial NSDK](https://www.nianticspatial.com/docs/nsdk/setup/),
  and porting this project would start from the
  [migration guide](https://www.nianticspatial.com/docs/nsdk/migration_guide/).
- AR-capable device (ARKit for iOS or ARCore for Android)

### Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/iamashkan/Semantic-Segmentation-using-Unity-and-Niantic-Lightship.git

