# Normal Fault Cross-Section Animation

A 3D interactive visualization of normal fault geological processes built with Three.js, designed for educational purposes to demonstrate earthquake mechanics and geological displacement.

Live demo link : (https://fault-simulator.vercel.app/)

## 🌍 Overview

This project creates an immersive 3D simulation that visualizes how normal faults work in geology. Users can interactively control fault parameters and observe real-time geological displacement, making it an excellent educational tool for understanding seismic processes.

## ✨ Features

### Interactive 3D Visualization
- **Real-time fault simulation** with customizable parameters
- **3D geological cross-section** showing footwall and hanging wall movement
- **Surface displacement animation** demonstrating earthquake effects
- **Interactive camera controls** (mouse rotation, zoom)
- -**DARK MODE**

### Educational Controls
- **Fault Angle Adjustment** (45°-85°) - Modify the dip angle of the fault plane
- **Displacement Control** (0-100m) - Simulate varying magnitudes of geological movement
- **Animation Speed** (0.2x-3x) - Control simulation playback speed
- **Earthquake Simulation** - Automated realistic fault movement
- **Reset Functionality** - Return terrain to original state

### Visual Elements
- Detailed geological layers (bedrock, topsoil)
- Surface features (houses, trees) to show displacement impact
- Semi-transparent fault plane visualization
- Realistic lighting and shadows
- Responsive design for all screen sizes

## 🚀 Getting Started

### Prerequisites
- Modern web browser with WebGL support
- No additional installations required

### Running the Application
1. Clone this repository:
   ```bash
   git clone [your-repository-url]
   cd normal-fault-visualization
   ```

2. Open `index.html` in your web browser
   - Double-click the file, or
   - Use a local server (recommended):
     ```bash
     python -m http.server 8000
     # Then visit http://localhost:8000
     ```

## 🎮 Usage Guide

### Basic Controls
- **Mouse**: Click and drag to rotate the 3D view
- **Mouse Wheel**: Zoom in/out
- **Control Panel**: Adjust geological parameters in real-time

### Simulation Steps
1. **Adjust Fault Angle**: Use the slider to set the fault plane angle
2. **Manual Displacement**: Drag the displacement slider to see gradual movement
3. **Earthquake Simulation**: Click "Simulate Earthquake" for automated realistic movement
4. **Reset**: Use "Reset Terrain" to return to initial state

### Educational Value
- Observe how the **hanging wall** (right side) drops relative to the **footwall** (left side)
- Notice how surface features are displaced during fault movement
- Understand the relationship between fault angle and displacement direction
- Visualize the impact of earthquakes on surface structures

## 🛠️ Technical Implementation

### Architecture
- **Three.js** (r128) for 3D graphics and WebGL rendering
- **Vanilla JavaScript** for interactive controls and animations
- **CSS3** for modern UI styling with glassmorphism effects
- **HTML5** semantic structure

### Key Components
- `NormalFaultSystem` class managing the entire 3D scene
- Geological block creation (footwall/hanging wall)
- Surface feature generation (houses, trees)
- Real-time displacement calculations
- Camera control system

### Performance Features
- Efficient shadow mapping
- Optimized geometry rendering
- Smooth animation loops
- Responsive controls

## 📚 Geological Background

### Normal Faults
Normal faults occur when the Earth's crust is under **extensional stress**, causing one block to drop down relative to another. Key characteristics:

- **Hanging Wall**: The block above the fault plane (drops down)
- **Footwall**: The block below the fault plane (relatively stable)
- **Fault Plane**: The fracture surface along which movement occurs
- **Displacement**: The amount of movement along the fault

## 🔧 Future Enhancements

Potential improvements for future versions:
- Additional fault types (reverse, strike-slip)
- Geological time scale animations
- Seismic wave visualization
- Multiple fault intersection scenarios
- Data export functionality for educational use

## 📱 Browser Compatibility

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ⚠️ Internet Explorer not supported (WebGL required)

## 🎨 Design Philosophy

The interface follows modern design principles:
- **Intuitive Controls**: Easy-to-understand sliders and buttons
- **Visual Clarity**: Clear distinction between geological layers
- **Educational Focus**: Information panels and guided interactions
- **Professional Appearance**: Clean, scientific aesthetic

## 📄 License

This project is created for educational purposes. Feel free to use and modify for non-commercial educational applications.

## 👨‍💻 Author

Created as a geological visualization project demonstrating:
- Advanced 3D web graphics programming
- Interactive educational software design
- Modern JavaScript and CSS techniques
- Scientific visualization principles

---
