# 🎥 Roblox Cinematic Freecam & Character Lock-On

A lightweight, universally compatible Luau execution script engineered specifically for Roblox video editors, content creators, and developers. It provides a smooth, Infinite Yield-style flying freecam while completely freezing player inputs so you can record character emotes, animations, and cinematic transitions flawlessly.

## ✨ Features

* **Complete Character Freeze:** Automatically disables local character inputs when activated, preventing you from accidentally walking out of frame or canceling an emote.
* **Dynamic Head-Lock (`L`):** Automatically toggles focus onto your avatar's head. The camera stays pinned to your vantage point but rotates dynamically to track your character's sways, jumps, dips, and emote movements.
* **On-the-Fly Speed Tuning:** Instantly dial in your perfect camera pan speed using dedicated hotkeys.
* **Clean Execution Loop:** Built-in automatic garbage collection prevents multiple execution instances from glitching or overlapping.

---

## 🎮 Controls

| Key | Action |
| :--- | :--- |
| **`F4`** | **Toggle Freecam** (Freezes character & detaches camera) |
| **`W, A, S, D`** | Pan Camera (Forward, Left, Backward, Right) |
| **`E` / `Q`** | Fly Camera Up / Down |
| **`Left Shift`** | Hold to sprint/boost camera speed |
| **`L`** | **Toggle Head Lock-On** (Keeps camera focused on your emote) |
| **`[`** (Left Bracket) | Decrease Freecam Speed |
| **`]`** (Right Bracket) | Increase Freecam Speed |

---

## 🚀 How to Use

1. Load into any Roblox experience.
2. Open your preferred Luau executor.
3. Paste the script from `script.lua` into your executor tab.
4. Inject and **Execute**.
5. Press **`F4`** to start flying!

---

## 🛠️ Installation / Script

```lua
-- loadstring(game:HttpGet('https://raw.githubusercontent.com/2dum4code/Self-Camlock/refs/heads/main/Script'))()
