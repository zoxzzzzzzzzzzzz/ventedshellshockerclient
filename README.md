# ventedshellshockerclient

```ascii
 ___      ___ _______   ________   _________  _______   ________          ________  ___       ___  _______   ________   _________   
|\  \    /  /|\  ___ \ |\   ___  \|\___   ___\\  ___ \ |\   ___ \        |\   ____\|\  \     |\  \|\  ___ \ |\   ___  \|\___   ___\ 
\ \  \  /  / | \   __/|\ \  \\ \  \|___ \  \_\ \   __/|\ \  \_|\ \       \ \  \___|\ \  \    \ \  \ \   __/|\ \  \\ \  \|___ \  \_| 
 \ \  \/  / / \ \  \_|/_\ \  \\ \  \   \ \  \ \ \  \_|/_\ \  \ \\ \       \ \  \    \ \  \    \ \  \ \  \_|/_\ \  \\ \  \   \ \  \  
  \ \    / /   \ \  \_|\ \ \  \\ \  \   \ \  \ \ \  \_|\ \ \  \_\\ \       \ \  \____\ \  \____\ \  \ \  \_|\ \ \  \\ \  \   \ \  \ 
   \ \__/ /     \ \_______\ \__\\ \__\   \ \__\ \ \_______\ \_______\       \ \_______\ \_______\ \__\ \_______\ \__\\ \__\   \ \__\
    \|__|/       \|_______|\|__| \|__|    \|__|  \|_______|\|_______|        \|_______|\|_______|\|__|\|_______|\|__| \|__|    \|__|
                                                                                                                                    
```
# Vented Client

A lightweight browser-based client wrapper for Shell Shockers with a custom UI, crosshair system, and modular features.

---

## 🚀 Features

### 🎮 Core

* Fullscreen toggle
* Reload system
* Draggable dock (with smooth movement)
* Hide all UI (`H` key)

---

### 🎯 Crosshair System

* Fully customizable via JSON
* Built-in presets (Dot, Classic)
* Overlay-based (does not modify the game)

Example:

```json
{
  "size": 20,
  "thickness": 3,
  "gap": 6,
  "color": "lime"
}
```

---

### 💾 Config System

* Automatically saves settings using `localStorage`
* Persists:

  * Crosshair configuration
  * UI preferences

---

### 🎹 Keybinds

| Key | Action     |
| --- | ---------- |
| H   | Toggle UI  |
| F   | Fullscreen |
| R   | Reload     |

---

### 🖥️ Display Modes

* Normal view
* 4:3 stretch
* Wide stretch

(Uses CSS scaling for visual effect)

---

## 📦 Usage

1. Download the HTML file
2. Open it in your browser
3. Click **Launch**
4. Customize using the dock

---

## 🧠 Future Plans

* Profile save/load system
* Theme editor
* Custom HUD builder
* Chrome extension version

---

## ⚠️ Disclaimer

This project is a **visual client wrapper** only.

It does not:

* Modify game files
* Inject into the game engine
* Interfere with servers

---

## 🛠️ Contributing

You can:

* Improve UI/UX
* Add new overlay features
* Expand customization systems

---

## 📜 License

MIT License
    
