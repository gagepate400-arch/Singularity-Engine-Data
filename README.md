# ProGen-Visual-Coding
# 🧬 ProGen Visual Coding® | Cloud Backend 🧬

This repository serves as the **Content Delivery Network (CDN)** and **Version Control** for the ProGen Visual Coding Plugin. By hosting the block library here, the engine stays updated in real-time without requiring manual marketplace updates.

## 🛠 Project Structure

* **/version.json**: Tracks the current build version and update status.
* **/Blocks_Library.json**: The master database of 500+ logic blocks, shapes, and Luau mappings.
* **/Engine_Core.lua**: Remote logic for the Jigsaw rendering engine.

## 📡 Remote Integration Links

To connect the Roblox Plugin to this backend, use the following **Raw** URLs in the plugin's bootloader:

* **Version Info:** `https://raw.githubusercontent.com/[YOUR_USERNAME]/[REPO_NAME]/main/version.json`
* **Block Library:** `https://raw.githubusercontent.com/[YOUR_USERNAME]/[REPO_NAME]/main/Blocks_Library.json`

## 🚀 Block Categories
The Singularity Engine currently supports:
* **Core Luau**: Logic, Math, Strings, Tables, and Metatables.
* **Roblox API**: DataStores, Raycasting, Pathfinding, and Networking.
* **Multi-Threading**: Native Parallel Luau (Actors/Synchronize).
* **Advanced CFrames**: Custom matrix operations and spatial math.

## 📊 Analytics
Critical reports are automatically generated in a "Receipt" format and transmitted via the system's internal telemetry. No personal user data or Roblox account information is ever transmitted.

---
**Developed for the Roblox Marketplace.** *Singularity Engine: "It's Scratch for Roblox, but better by millions."*


 
# Created, Owned, Managed, And Updated By Ezz Studios®.
## Ezz Studios® Discord Link: https://discord.gg/RyTqGkUpyW
