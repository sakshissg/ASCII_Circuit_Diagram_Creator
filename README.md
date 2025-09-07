# ASCII Circuit Diagram Creator

A **web-based tool** for creating ASCII circuit diagrams with an intuitive click-to-place interface.  
Perfect for simple circuit diagrams for **documentation, educational purposes, or quick sketches**.

---

## ✨ Features

### 🔧 Component Library
- **Wire**: Horizontal (`----`) and vertical (`│`) connections  
- **Cell/Battery**: Power source with polarity indicators  
- **Bulb**: Light bulb representation `((O))`  
- **Switch**: Circuit switch `/`  
- **Resistor**: Resistance element (`^^^^` or `ΛVΛ`)  

### 🎯 Smart Placement
- **Dual Orientation**: Place components horizontally or vertically  
- **Grid-based**: Precise alignment with visual grid overlay  
- **Click-to-place**: Select component → choose orientation → click to place  

### ⏮️ Undo/Redo System
- Full history tracking (up to **50 operations**)  
- Smart state management (only saves when components are placed)  
- Visual feedback (buttons enable/disable automatically)  

### 💾 Export Options
- **Download as `.txt`** file  
- **Copy to clipboard** with one click  
- **Clean formatting** with automatic trimming of trailing spaces  

---

## 🚀 How to Use

1. **Select a Component**  
   Click a component in the toolbar (Wire, Cell, Bulb, Switch, Resistor). Selected button = highlighted blue.

2. **Choose Orientation**  
   - **Horizontal** → left-to-right placement  
   - **Vertical** → top-to-bottom placement  

3. **Place Components**  
   Click on the white canvas grid. Components snap to the character grid.

4. **Edit Your Circuit**  
   - Undo (↶) → remove last component  
   - Redo (↷) → restore undone component  
   - Clear → start fresh  

5. **Export Your Work**  
   - **Export** → download as `.txt`  
   - **Copy to Clipboard** → paste ASCII diagram elsewhere  

---

## 🖼️ Example Circuit
