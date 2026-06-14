# AeroStrike

AeroStrike is a fast-paced, browser-based aerial combat simulator. Pilot a highly maneuverable fighter jet, engage enemy aircraft in dogfights, and complete your primary mission: **sinking the enemy cruiser**.

Built with **JavaScript** and the **Three.js WebGL library**, AeroStrike delivers a smooth 3D experience directly in your browser with realistic flight physics and tactical combat systems.

---

## 🌐 Play the Game
[Play AeroStrike on Itch.io](https://aamir-pa2009.itch.io/aerostrike)

---

## 🎮 Controls

| Action             | Key             |
|--------------------|-----------------|
| **Steer (Yaw)**    | A / D           |
| **Pitch**          | Up / Down       |
| **Throttle**       | W / S           |
| **Fire Missile**   | Space           |
| **Deploy Flares**  | F               |
| **Zoom View**      | Z               |
| **Toggle Camera**  | C               |
| **Lock Target**    | Click Target    |
| **Pause Game**     | P               |

---

## 📊 HUD & Systems Overview

The tactical Head-Up Display (HUD) provides critical flight data:

*   **Flight Data**: Real-time Altitude (ft) and Airspeed (kts) indicators.
*   **Integrity**: A visual health bar monitoring aircraft structural damage.
*   **Armament**: Missile count and target locking status.
*   **Threat Detection**: Visual "MISSILE ALERT" HUD indicator and synchronized audio warning tones.
*   **Radar**: A 3D-to-2D mapped radar system showing the enemy cruiser (Red) and hostile jets (Green).
*   **Landing Gear**: Automated gear system that deploys during low-altitude carrier approaches.

---

## 🧭 Mission Objective

Your primary objective is to locate and destroy the enemy cruiser. 

1.  **Engage**: Use your radar to find the target ship.
2.  **Dogfight**: Defend yourself against intercepting enemy jets.
3.  **Countermeasure**: Use flares to decoy incoming homing missiles.
4.  **Rearm**: If you run low on ammo or health, return to the carrier deck for a full repair and rearm.

---

## 🛠️ Technical Implementation

### Flight & Physics
*   **Aerodynamics**: Simulated pitch, roll, and yaw with speed-dependent maneuverability.
*   **Carrier Ops**: Precision deck detection for landing and rearming.
*   **Environment**: Dynamic ocean waves and procedural cloud generation.

### Weapons & AI
*   **Homing Missiles**: Vector-based tracking logic that can target both ships and aircraft.
*   **Countermeasures**: Flare physics that actively divert enemy missile tracking.
*   **Enemy AI**: Pursuit-based flight logic for hostile jets with tactical missile deployment.

### Rendering
*   **Engine**: Powered by **Three.js** for high-performance WebGL 3D rendering.
*   **FX**: Custom particle systems for explosions, engine exhaust, and smoke trails.
*   **Audio**: Synthesized real-time audio for engine, combat, and warning systems.

---

## 🎥 Gameplay
[Watch the AeroStrike Gameplay Video](https://youtu.be/P-ykU11OTvg)