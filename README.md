# Simple Raster G-code Generator for Foam Cutting CNCs (CostyCNC Demo)

[🔗 Try the Web App](https://costycnc.github.io/raster-gcode-cm10/)

This is a **beginner-friendly**, web-based tool to convert black-and-white images into raster-style G-code optimized specifically for **foam cutting CNC machines**, like the CostyCNC.

> ⚠️ **NOTE:** This version is only a demo. It does **not control motors** or connect to a real machine. The full working version is integrated in the CostyCNC system via the MKS DLC32 board.

---

## 🌟 What Makes This Tool Unique?

Unlike typical G-code generators (including those for laser cutters), this tool creates **continuous, optimized cutting paths** designed specifically for **polystyrene foam cutting**.

Key characteristics:

- Generates a **single continuous cutting line**  
- The cutting path **enters and exits object interiors seamlessly**  
- Connects multiple objects with the same cutting line, forming one unbroken path  

This approach is essential for cutting polystyrene foam, where the cut must be continuous without interruptions. Such specialized path planning is rare and tailored specifically for lightweight foam cutting CNC machines.

---

## 🛠️ Who Should Use This?

- 🟢 **New CNC users** working with foam cutters who need a simple, effective tool  
- 🟦 **Hobbyists and educators** focusing on polystyrene and lightweight materials  
- 🔧 **CostyCNC owners** wanting to understand their onboard software  
- ❌ **Not suitable for laser cutters or general CNC machines**

---

## ⚙️ Key Features

- Converts black & white images (PNG, JPG) into optimized continuous G-code paths  
- Adjustable resolution and feedrate  
- Preview cutting paths before generating G-code  
- Download `.nc` files ready for CostyCNC or similar foam cutting machines  
- Built with just HTML + JavaScript — no external dependencies

---

## 🔌 For Real CNC Control

To control real motors and execute jobs, connect to the **CostyCNC's Wi-Fi network** and open its internal interface:

1. Connect to the MKS-DLC32 WiFi hosted by your CostyCNC machine  
2. Select `CostyCNC` from the interface menu  
3. The full version opens with motor control and live job execution

---

## 📁 Files

- `index.html`: Main web app with embedded JavaScript  
- Lightweight and portable — no external libraries  

---

## 🔍 Keywords (for search)

- G-code generator for foam cutter  
- Continuous path CNC cutting  
- Raster to optimized G-code for polystyrene  
- CostyCNC foam cutter software  
- MKS DLC32 CNC web interface  
- Beginner CNC foam cutting tool  
- Lightweight CNC raster path generator  

---

## 📄 License

Open-source under the [MIT License](LICENSE).

---

## 🙌 Credits

Created by [CostyCNC](https://github.com/costycnc)  
Built for users who need **simple, specialized tools** instead of complex, generic CNC software.

