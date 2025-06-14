# 🎨 Vertex Colours for Substance Painter (V.C.S.P)

**Quick vertex coloring tool for Blender, designed for generating ID maps for Substance Painter.**  
This add-on assigns a single vertex color to selected mesh objects — either a user-defined color or a unique random one per object.

---

## ✨ Features

- 🎯 Assign a **solid vertex color** to one or more selected mesh objects.
- 🎲 Optional **random color** per object.
- 🧱 Automatically creates vertex color layers if missing.
- 🎛 Auto-generates a viewport material using vertex colors (so you see the result instantly).
- 🧰 Minimal UI integrated into the **N-panel** (right sidebar in 3D Viewport).

---

## 🖼 Example

| Randomize OFF (Same Color) | Randomize ON (Unique Colors) |
|----------------------------|------------------------------|
| ![solid](https://via.placeholder.com/150) | ![random](https://via.placeholder.com/150) |

---

## 🛠 Installation

1. Download or clone this repository.
2. In Blender:
   - Go to `Edit > Preferences > Add-ons`.
   - Click **Install** and select the downloaded ZIP file.
   - Enable the checkbox next to **"Vertex Colours for Substance Painter (V.C.S.P)"**.

---

## 🚀 Usage

1. Select one or more **mesh objects**.
2. Open the **N-panel** (press `N`) in the 3D Viewport.
3. Navigate to the **"To Substance Painter"** tab.
4. Pick a color or enable **Randomize**.
5. Click **Assign Color**.

---

## 🧠 Notes

- Vertex colors are applied **uniformly per object** (all faces and loops).
- This is ideal for **ID masking** workflows in tools like **Substance Painter**.
- If no material is present, one is created and linked automatically.

---

## 👨‍💻 Author

**Piotr Rutkowski**  
Maintainer of V.C.S.P

---

## 📝 License

This project is licensed under the  
**Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)**  
[Read the full license](https://creativecommons.org/licenses/by-nc-sa/4.0/)

You are free to:
- Share — copy and redistribute the material in any medium or format
- Adapt — remix, transform, and build upon the material

Under the following terms:
- **Attribution** — You must give appropriate credit.
- **NonCommercial** — You may not use the material for commercial purposes.
- **ShareAlike** — If you remix, transform, or build upon the material, you must distribute your contributions under the same license.

