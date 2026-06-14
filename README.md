# AeroStrike

A fast‑paced browser‑based aerial combat game where you pilot a fighter jet on a mission to **sink an enemy cruiser**.  
Built entirely with **HTML, CSS, and JavaScript** in a single file — lightweight, fast, and instantly playable.

---

## 🌐 Play the Game  
https://aamir-pa2009.itch.io/aerostrike

---

## 🎮 Controls

| Action            | Key            |
|------------------|----------------|
| Steer            | A / D          |
| Pitch            | Up / Down      |
| Throttle         | W / S          |
| Fire Bomb        | Space          |
| Deploy Flares    | F              |
| Zoom             | Z              |
| Camera Toggle    | C              |
| Lock Target      | Click Ship     |
| Pause            | P              |

---

## 📊 HUD Overview

- Altitude (ft)  
- Airspeed (kts)  
- Integrity (health bar)  
- Bomb Count  
- Missile Warning Indicator  
- Radar showing enemy jets and cruiser  
- Mission Objective  
- Gear Status (auto‑gear)

---

## 🧭 Objective

Destroy the enemy cruiser before your jet takes critical damage.  
Survive enemy jets, avoid homing missiles, manage ammo, and return to the carrier to rearm.

---

# 🛠️ Updated Systems & Techniques Used

AeroStrike now includes a wide range of real‑time systems, all implemented in pure HTML, CSS, and JavaScript.

---

## ✈️ Flight & Physics

- Smooth pitch, roll, yaw, and throttle simulation  
- Auto‑landing gear (down on ground, up in air)  
- Touchdown smoothing  
- Ground detection using `groundY`  
- Carrier deck detection (`onDeck`)  
- Crash detection for hard landings or overspeed  

---

## 💥 Weapons & Countermeasures

### Bombs
- Distance‑based collision detection with the enemy cruiser (`enemyShip`)  
- Configurable cruiser HP  
- Explosion effects  

### Enemy Missiles
- Homing logic using vector math  
- Smooth steering and orientation  
- Missile lifetime and cleanup  
- Missile proximity warning tone  

### Flares
- Burst flare system  
- Missiles can retarget flares  
- Flare lifetime and decay  

---

## 🤖 Enemy AI

### Enemy Jets
- Primitive‑mesh fighter models  
- Pursuit AI  
- Missile firing logic  
- Increasing difficulty per level  
- Radar blips  

### Enemy Cruiser
- HP system  
- Bomb collision detection  
- Radar blip  
- Mission completion trigger  

---

## 📡 Radar System

- 2D radar overlay  
- World‑to‑radar coordinate scaling  
- Clamped blip positions  
- Tracks jets and cruiser  

---

## 🔊 Audio Systems

- Missile warning tone  
- Explosion sounds  
- UI feedback sounds  

---

## 🛬 Carrier Operations

- Auto‑gear down on landing  
- Safe landing detection  
- Rearming system:
  - Restores bombs  
  - Restores HP  
  - HUD message: “REARMING COMPLETE”  

---

## 🧩 Rendering & Architecture

- Manual 3D object groups (jets, missiles, flares)  
- Frame‑based update loop  
- Efficient array cleanup  
- HUD built with HTML/CSS  
- Particle effects  
- No external libraries required  

---

# ✨ Features

- Smooth jet movement  
- Dogfighting enemy jets  
- Homing missiles + flares  
- Carrier landing + rearming  
- Radar tracking  
- Explosion effects  
- Level progression  
- Fully browser‑playable  

---

## 🚀 Planned Improvements

- Choosable difficulty levels
- Additional enemy ships or aircraft types
- Score system  
- Multiplayer Combat
- Settings menu  
- Mobile controls  
- More particle effects   

---

## 📦 Hosting

Built for HTML5 Canvas and deployed on Itch.io for instant play.

## 🎥 Gameplay Video
[![Watch the video](https://img.youtube.com/vi/YOUR_VIDEO_ID/0.jpg)](https://youtu.be/P-ykU11OTvg)

git add .
git commit -m "Updated AeroStrike build"
git push origin main
