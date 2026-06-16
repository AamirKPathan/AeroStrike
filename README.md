# AeroStrike

AeroStrike is a fast-paced, browser-based aerial combat simulator. Pilot a highly maneuverable fighter jet, engage enemy aircraft in dogfights, and complete your primary mission: **sinking the enemy cruiser**.

Built with **JavaScript** and the **Three.js WebGL library**, AeroStrike delivers a smooth 3D experience directly in your browser with realistic flight physics and tactical combat systems.

---

## 🌐 Play the Game
[Play AeroStrike on Itch.io](https://aamir-pa2009.itch.io/aerostrike)

---

## 🎮 Controls
The game features an integrated **Bottom Control Bar** for quick reference during flight.

| Action             | Key             |
|--------------------|-----------------|
| **Steer (Yaw)**    | A / D           |
| **Pitch**          | Up / Down       |
| **Throttle**       | W / S           |
| **Fire Missile**   | Space           |
| **Deploy Flares**  | F               |
| **Zoom View**      | Z               |
| **Lock Target**    | Click Target    |
| **Pause Game**     | P               |

---

## 📊 HUD & Systems Overview

The tactical Head-Up Display (HUD) has been **minimalized** to provide a clear field of view while maintaining critical flight data:

*   **Flight Data**: Real-time Altitude (ft) and Airspeed (kts) indicators located in the top-left.
*   **Integrity**: A streamlined health bar monitoring aircraft structural damage.
*   **Armament**: Missile count and target locking status.
*   **Threat Detection**: Visual "MISSILE ALERT" HUD indicator and synchronized audio warning tones.
*   **Radar**: A 3D-to-2D mapped circular radar system showing targets.
*   **Landing Gear**: Automated gear system that deploys during low-altitude carrier approaches.

![Hud Radar](media/Screenshot%202026-06-14%20132613.png)
![Altimeter and ASI](media/Screenshot%202026-06-14%20132632.png)
![Ammo, Gear, And Health](media/Screenshot%202026-06-14%20132644.png)

---

## 🧭 Mission Objective

Your primary objective is to locate and destroy the enemy cruiser. 

1.  **Engage**: Use your radar to find the target ship.
2.  **Dogfight**: Defend yourself against intercepting enemy jets.
3.  **Countermeasure**: Use flares to decoy incoming homing missiles.
4.  **Rearm**: If you run low on ammo or health, return to the carrier deck for a full repair and rearm.

![Mission Objectives](media/Screenshot%202026-06-14%20130917.png)

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


---

## 🤫 Upcoming
*   **Openworld**: No level, pure fun, rack up points and get your name on the leaderboard.
*   **Accounts**: Accounts and leaderboard coming soon
*   **Ground**: Ground based battles coming soon
*   **Campaigns**: Proper story mode campaigns will emerge soon.
*   **Multiplayer**: Multiplayer combat and multiplayer co-op servers to be added. 