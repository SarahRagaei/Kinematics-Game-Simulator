# 🎮 Kinematics Game Simulator

An interactive desktop app built with **PyQt5** and **Matplotlib** that simulates javelin throwing using projectile motion physics. Users can explore motion dynamics by adjusting parameters and viewing real-time trajectories, all in a playful game-like environment.


## ✨ Features

- 🎯 **User-Controlled Parameters**:
  - Firing angle (30° to 90°)
  - Launching speed (5 to 40 m/s)
  - Display (animation) speed

- 🕹️ **Interactive Controls**:
  - Play / Pause animation
  - Restart simulation
  - Real-time animation updates

- 📊 **Live Trajectory Visualization**:
  - 2D graph of height vs. distance
  - Dynamic max height, distance, and flight time updates
  - Javelin represented with directional marker

- 🧠 **Physics-Based Calculations**:
  - Accurate motion equations
  - Real-time computation of flight parameters
  - Transparent matplotlib overlay on custom background image


## 🎬 Demo Video

This video demonstrates:
- Using controls: **Play/Pause**, **Restart**, and **Display Speed** slider
- Changing **firing angle** while keeping the same speed:
  - 45° (optimal range)
  - < 45° (lower, faster arc)
  - \> 45° (higher, shorter arc)
  - 90° (maximum height, zero distance)
 
<div align="center">
  <a href="https://www.youtube.com/watch?v=3fM7YInp_94&autoplay=1" target="_blank">
    <img src="https://img.youtube.com/vi/3fM7YInp_94/0.jpg" alt="Demo Video Thumbnail" width="640">
  </a>
</div>


## ⚙️ Tech Stack

- **Python**
- **PyQt5** – for the GUI and layout
- **Matplotlib** – for real-time plotting
- **NumPy** – for numerical calculations
- **Custom assets** – background, icons, images


## 🚀 Getting Started

1. Clone the repository:
```
git clone https://github.com/your-username/Kinematics-Game-Simulator.git cd Kinematics-Game-Simulator
```

4. Install the required packages:
```
pip install PyQt5 matplotlib numpy
```

3. Run the application:
```
python main.py
```

## 📂 Folder Structure

Kinematics-Game-Simulator/

├── Images/ # All visual assets

│ ├── area.png

│ ├── athlete_stages.png

│ ├── field.png

├── icons.py

├── images.py

├── main.py

├── project_ui.ui

├── project_ui_ui.py
