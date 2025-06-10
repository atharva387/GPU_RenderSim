# 🚀 GPU-RenderSim

🧊 Real-time 3D rendering demo in C++ using OpenGL.  
Features a free-fly FPS-style camera, multiple rotating cubes, transformation matrices, and custom GLSL shaders — built from scratch using GLFW, GLAD, and GLM.

Ideal for showcasing your understanding of the GPU graphics pipeline and 3D math in interviews and portfolios.

---

## 📸 Demo Preview

> 🖼️ Add a screenshot here: `assets/screenshot.png`

![demo-preview](./assets/screenshot.png)

---

## 🔧 Features

- ✅ Real-time rotating 3D cubes
- ✅ WASD + mouse-based camera navigation
- ✅ MVP transformations (model/view/projection)
- ✅ Shader-based rendering (GLSL)
- ✅ Depth buffering for proper 3D visibility
- 🖼️ GitHub-ready structure for easy cloning and building

---

## 🎮 Controls

| Key / Input | Action |
|-------------|--------|
| `W` / `S`   | Move forward / backward |
| `A` / `D`   | Strafe left / right |
| `Mouse Move` | Look around (yaw/pitch) |
| `Esc`       | Exit window |

---

## 📦 Tech Stack

- **C++** – Core language
- **OpenGL (3.3 Core)** – Graphics API
- **GLFW** – Windowing + Input
- **GLAD** – OpenGL function loader
- **GLM** – Matrix math (MVP, vectors, camera)

---

## 📂 Project Structure

GPU-RenderSim/
├── shaders/
│ ├── vertex_shader.glsl
│ └── fragment_shader.glsl
├── assets/
│ └── screenshot.png # Add your own preview
├── src/
│ └── main.cpp
├── .gitignore
├── README.md
└── CMakeLists.txt (optional)