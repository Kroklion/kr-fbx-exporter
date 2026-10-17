# FBX Exporter with Fixes and Extensions

A fork of Blenders FBX exporter.

## Features

**Fixes for "Apply Transform" Problems**
   - Object transforms break on every second relation
   - Armature orientation not baked


**Fix for Unit settings**
   - Scale of armature is 100, first bone 0.01 with FBX exporter default scale setting. Units can now be left at default in both Blender and Unity while **"Apply Transform"** is active.

---

## Installation
1. **Download:**  
   Download the repository as a ZIP file (Code → Download ZIP).

2. **Install the Add-on:**  
   In Blender, navigate to:
   - **Edit > Preferences > Add-ons > Add-Ons Settings** (click the dropdown symbol)
   - Select **Install from Disk** and point to the downloaded ZIP file.

## Usage

**kr FBX (.fbx)** appears under File > Export. Use like the official FBX exporter.


## Requirements

* Blender 5.2 minimum version for now.

---

## License

This project is licensed under the terms of the [GNU General Public License v2.0](LICENSE).

---

## Acknowledgements

This project forks Blender's **io_scene_fbx** core addon, specifically the Python FBX exporter.
