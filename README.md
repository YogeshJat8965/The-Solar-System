# 🌌 3D Solar System Explorer

An immersive 3D solar system simulation built with **THREE.js** and **Vite**. Experience our solar system with realistic physics, stunning visuals, and interactive features.


## 🚀 Quick Start

### Prerequisites
- **Node.js** (v14 or higher)
- **npm** or **yarn**

### Installation & Setup
```bash
# Clone the repository
git clone <your-repo-url>
cd Solar-System-3D

# Install dependencies
npm install

# Start development server
npm run dev

```

The application will open at `http://localhost:5173`

## ✨ Features

### 🪐 **Complete Solar System**
- All 8 planets + Pluto with accurate textures and scaling
- Realistic orbital mechanics and rotation speeds
- Individual speed controls for each planet

### 🌙 **Moons & Satellites**
- **Earth**: Moon with realistic orbit
- **Mars**: Phobos & Deimos (3D models)
- **Jupiter**: Io, Europa, Ganymede, Callisto

### 🎨 **Visual Effects**
- **Bloom Effect**: Glowing sun with adjustable intensity
- **Outline Pass**: Planet highlighting on hover
- **Day/Night Shader**: Earth's realistic day/night cycle
- **Atmospheric Effects**: Venus and Earth atmospheres
- **Ring Systems**: Saturn and Uranus rings

### 🎮 **Interactive Controls**
- **Mouse Navigation**: Orbit, zoom, and pan
- **Planet Selection**: Click planets for detailed information
- **Control Panel**: Adjust orbit speeds, rotation, and sun intensity
- **Pause/Resume**: Animation control button

### 🌌 **Environment**
- **Starfield Background**: Realistic space environment
- **Dynamic Lighting**: Point light from sun with shadows
- **Asteroid Belts**: 
  - Main belt (1000 asteroids between Mars & Jupiter)
  - Kuiper belt (3000 asteroids beyond Neptune)

### 📊 **Planet Information System**
- Detailed data for each planet (radius, tilt, rotation period, etc.)
- Interactive info panels with close-up views
- Smooth camera transitions

## 🛠️ Technology Stack

- **THREE.js** - 3D graphics library
- **Vite** - Build tool and dev server
- **dat.GUI** - Interactive controls
- **GLSL Shaders** - Custom materials and effects

## 🎯 Controls

| Action | Control |
|--------|---------|
| Rotate View | Left Mouse + Drag |
| Zoom | Mouse Wheel |
| Pan | Right Mouse + Drag |
| Select Planet | Left Click on Planet |
| Pause/Resume | Pause Button (Top Left) |
| Adjust Settings | Control Panel (Top Right) |

## 📁 Project Structure

```
├── src/
│   ├── index.html          # Main HTML file
│   ├── script.js           # Main JavaScript application
│   ├── style.css           # Styling
│   └── images/             # Planet textures and models
├── static/                 # Static assets
├── package.json           # Dependencies
└── vite.config.js         # Vite configuration
```

## 🔧 Key Components

- **Planet Creation Function**: Modular planet generation with textures, bumps, rings, and atmospheres
- **Orbital Mechanics**: Realistic scaled distances and rotation periods
- **Shader Materials**: Custom GLSL shaders for Earth's day/night cycle
- **Post-processing Pipeline**: Bloom and outline effects
- **3D Model Loading**: GLTF models for irregular moons

## 🎮 Usage Tips

1. **Explore Planets**: Hover over planets to see outlines, click for detailed information
2. **Customize Experience**: Use the control panel to adjust speeds and effects
3. **Best Performance**: Use the pause button when adjusting multiple settings
4. **Mobile**: Responsive design works on tablets and mobile devices

**Enjoy exploring the cosmos! 🚀✨**
