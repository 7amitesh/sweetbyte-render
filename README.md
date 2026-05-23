# 🍩 SweetByte Render

![Blender](https://img.shields.io/badge/Blender-F5792A?style=flat&logo=blender&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat)
![Year](https://img.shields.io/badge/Started-2020-blue?style=flat)

A personal Blender project repository — two projects built from scratch while learning 3D modeling, shading, lighting, and rendering workflows. Started in 2020 out of pure curiosity, this repo documents the journey from a first-ever 3D model to a fully lit cinematic scene.

---

## 📁 Repository Structure

```
sweetbyte-render/
├── spider 4 leg.blend              # Spider creature — first 3D project (2020)
├── donut.blend 2.0.blend           # Stylized cinematic donut scene
├── blend1.gif                      # Donut render preview
└── blend2.gif                      # Spider render preview
```

---

## 🍩 Project 1 — Donut Scene

![Donut Demo](https://github.com/7amitesh/sweetbyte-render/blob/main/blend1.gif?raw=true)

A cinematic stylized 3D dessert environment — this was where things started getting serious and making more better version models. After getting comfortable with basic modeling, I wanted to push into realistic shading and proper lighting composition. The donut became the perfect canvas for learning procedural materials, glaze shading, and cinematic depth of field.

**What I focused on:**
- Procedural material nodes for icing and glaze texture
- HDRI and three-point cinematic lighting setup
- Depth of field and camera composition
- Cycles render for realistic light bounce

**File:** `donut.blend 2.0.blend`

---

## 🕷️ Project 2 — Spider Creature (2020)

![Spider Demo](https://github.com/7amitesh/sweetbyte-render/blob/main/blend2.gif?raw=true)

This was my very first 3D project — made in 2020 when I had just opened Blender for the first time. I picked a spider because it had enough geometric complexity to actually learn from — a round body, segmented limbs, multiple legs to rig — without being impossible to finish. No tutorial base, just references and a lot of undoing mistakes.

**What I focused on:**
- Multi-limb geometry and symmetry modeling
- Subdivision surface workflow
- Basic 4-leg rig structure
- Lighting setup and first Cycles render

**File:** `spider 4 leg.blend`

---

## 🚀 How to Open These Files

**Requirements**
- [Blender 3.x or above](https://www.blender.org/download/) — free and open source

**Steps**

```bash
# 1. Clone this repository
git clone https://github.com/7amitesh/sweetbyte-render.git

# 2. Open Blender
# Go to: File → Open → select the .blend file you want

# 3. Useful controls:
#    F12          → render current frame
#    Ctrl + F12   → render full animation
#    Numpad 0     → switch to camera view
#    Spacebar     → play animation in viewport
```

> 💡 If Blender shows a version warning on open, click **"Load Anyway"** — files open fine on Blender 3.x and above.

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| Blender (Cycles) | Rendering, shading, modeling |
| Shader Node Editor | Procedural materials |
| Blender Rigging Tools | Spider leg rig |
| EEVEE | Viewport previews |

---

## 📌 Notes for Contributors

- Both `.blend` files are self-contained — all textures and materials are packed inside
- If textures appear pink or missing, go to: `File → External Data → Find Missing Files`
- Render settings are saved inside each file — no extra configuration needed
- Tested on Blender `3.6 LTS`

---

## 📬 Contact

**Amitesh** · [github.com/7amitesh](https://github.com/7amitesh)
