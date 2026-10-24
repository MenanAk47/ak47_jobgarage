**The ultimate job garage management experience for FiveM servers.** ak47_jobgarage provides a comprehensive, fully in-game solution to create, configure, and manage vehicle garages for any job. Featuring an intuitive 3D placement builder, rank-based vehicle permissions, on-the-spot vehicle servicing (repair, refuel, livery, extras, wash), and native `ak47_lib` multi-framework support.

---

## 🎥 Showcase
<img width="1920" height="1080" alt="thumbnail" src="https://github.com/user-attachments/assets/9066e5a2-b25d-4b85-b30c-46700f43926e" />

> **[Click here to watch the full feature showcase on YouTube](https://youtu.be/hq3kxBBrVJ8)**

---


## 🔥 Key Features

Designed to improve roleplay immersion and economy balancing:

### 🏗️ In-Game Creation & Administration

* **Visual 3D Builder & PolyZone Setup:** Admins can effortlessly create new job garages in-game using interactive PolyZone boundary drawing and a 3D scripted camera to position and rotate preview spawn points with precision controls.
* **Live In-Game Garage Editor:** Edit existing garages anytime using `/jobgaragesetting` to modify blip visibility, sprite, color, size, vehicle categories, and toggle individual garage service features without restarting the server.
* **Flexible Admin Access Control:** Secure admin commands (`/createjobgarage`, `/jobgaragesetting`, `/deletejobgarage`) with ACE permissions, Rockstar licenses, identifiers, or framework user groups (`admin`, `superadmin`, `god`).

### 🚘 Multi-Vehicle Types & Job Rank Authorization

* **Universal Vehicle Type Support:** Dedicated setup options for ground vehicles (cars/bikes), helicopters, airplanes, and sea craft (boats/submarines) with accurate water detection probing.
* **Rank-Based Vehicle Access:** Restrict high-performance or specialized job vehicles to specific ranks or grades within the job hierarchy.
* **Configurable Grade Hierarchy:** Option to allow higher-ranking officers to access all lower-rank vehicles or strictly enforce exact rank requirements.

### 🔧 Quick Service & Modification Options

* **Instant Vehicle Repair & Cleaning:** Built-in options menu allowing drivers to repair damage, fix vehicle deformation, and clean away dirt using progress bars.
* **Livery & Extras Switcher:** Real-time menus to easily switch vehicle liveries or toggle vehicle extras (0–14) via interactive UI checkboxes.
* **Integrated Fuel Top-Up:** Refuel job vehicles directly inside the garage zone with automatic framework and fuel script compatibility.

### 📍 Smart Spawning & Dock Repositioning

* **Intelligent Spawn Point Detection:** Automatically scans defined spawn points and selects the closest unobstructed point, preventing vehicle stacking and collisions.
* **Dock Exit Repositioning:** Custom exit coordinates for boat garages that automatically teleport the driver and passengers safely onto docks when storing watercraft.
* **Automatic Keys & Cleanup:** Seamlessly grants vehicle keys upon spawn, cleans dirt, applies predefined vehicle modifications, and handles safe despawning upon vehicle return.

### 🛠️ Technical Excellence

* **Multi-Framework & Target Support:** Seamlessly works with ESX, QB, QBX, and various target systems (ox_target, qb-target, qtarget).
* **Highly Secure:** Built-in server-side exploit checks, including distance validation and trigger authentication, to prevent cheating.
* **Automated Database & Core Integrations:** Features automated MySQL database creation with legacy table migration support, zero-idle PolyZone optimization, and seamless key and fuel integrations via `ak47_lib`.

---

## 💻 Framework:

* ESX, QB, QBX

---

## ⚙️ Dependencies:

* ak47_lib: https://github.com/MenanAk47/ak47_lib/releases/latest

---

## ⚙️ How To Install:

* Download ak47_jobgarage from your cfx portal.
* Add the script in your resources folder.
* Add items based on your framework instruction.
* Add item images into inventory.
* Start the script in your server.cfg below framework files.
* Make sure you have all dependencies.
* Restart the server.

---

## 🔗 Links & Support:

* **📖 Documentation:** [https://docs.menanak47.com/multi-framework/ak47_jobgarage](https://docs.menanak47.com/multi-framework/ak47_jobgarage)
* **🛒 Buy Now (Tebex):** [https://menanak47.tebex.io/package/6222271](https://menanak47.tebex.io/package/6222271)
* **💬 Discord Support:** [https://discord.gg/menanak47](https://discord.gg/menanak47)

---

## 📝 Note:
* We don't support custom framework. Make sure you are using official framework update.
* Renaming the script is not allowed. It may break the functionalities.
* Don't upload the script with FileZilla, Use Winscp if you are using FTP for file uploading
