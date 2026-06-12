# 🎥 Roblox Cinematic Freecam & Multi-Target Orbit Studio

A lightweight, high-performance Luau execution script engineered specifically for Roblox cinematic directors, content creators, and developers. It provides a highly fluid, Infinite Yield-style flying freecam combined with an interactive user interface panel that lets you track single or multiple players simultaneously with ultra-smooth, customizable orbital physics.

## ✨ Features

* **Multi-Target Center Mass Orbit:** Select single or multiple players from the interface. The camera automatically calculates the fluid midpoint between all chosen targets and drops into an orbital tracking mode.
* **Persistent Roster Locking:** Toggling freecam off and back on preserves your exact player selection. The camera immediately snaps right back into tracking mode without requiring you to re-engage the roster list.
* **Intuitive Dual-Input FOV Slider:** Seamlessly zoom your field of view dynamically using either the interactive slider bar or precise text inputs to craft the perfect lens focal length.
* **Balanced Orbit & Speed Mechanics:** Integrated speed balancing ensures standard flight mode matching. Use calibrated orbital zoom adjustments (`W`/`S`) and vertical panning (`E`/`Q`) scaled exactly to rotational tracking speed.
* **Reversed Fluid Smoothness Mapping:** Complete cinematic control via a real-time slider where higher numerical values directly equate to more fluid, high-drag, sweeping camera glides.
* **Clean Execution Loop:** Built-in automatic garbage collection instantly terminates old execution loops, preventing UI or state overlap upon re-injection.

---

## 🎮 Controls

### System & Interface Controls
| Key | Action |
| :--- | :--- |
| **`F4`** | **Toggle Freecam Mode** (Detaches camera & freezes local character input) |
| **`K`** | **Toggle Studio Setup Panel** (Opens and closes the interface script configuration window) |

### Freecam Flight Mode (No Targets Selected)
| Key | Action |
| :--- | :--- |
| **`W` / `S`** | Fly Forward / Backward |
| **`A` / `D`** | Fly Left / Right |
| **`E` / `Q`** | Fly Straight Up / Straight Down |
| **`Left Shift`** | Hold to multiply fly speed |
| **`Right Click + Drag`** | Lock cursor and look around |

### Multi-Target Orbit Mode (Targets Active in UI)
| Key | Action |
| :--- | :--- |
| **`A` / `D`** | Orbit left and right around targets |
| **`E` / `Q`** | Orbit vertically up and down over targets |
| **`W` / `S`** | Glide camera physical distance Closer (Zoom In) / Further (Zoom Out) |
| **`Left Shift`** | Hold to accelerate orbit panning speed |

### Speed Modifiers
| Key | Action |
| :--- | :--- |
| **`[`** (Left Bracket) | Decrease camera base speed parameter |
| **`]`** (Right Bracket) | Increase camera base speed parameter |

---

## 🚀 How to Use

1. Load into any Roblox experience.
2. Open your preferred Luau executor.
3. Paste the source script into your executor tab.
4. Inject and **Execute**.
5. Press **`F4`** to engage the camera, and press **`K`** to configure your tracking targets!

---

## 🛠️ Installation / Script

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/2dum4code/Self-Camlock-Script/refs/heads/main/Script"))()
