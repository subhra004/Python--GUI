# An interactive visualization toolkit for 3D geometric modeling and data visualization using Python.




This project presents a Python-based 3D visualization tool for representing **atomic configurations within a crystal lattice** using unit cells. Designed with computational material science in mind, the tool provides an extensible way to inspect which unit cells in a lattice contain atoms, leveraging `matplotlib`'s 3D plotting capabilities.

---

## 🔧 Overview

This Jupyter Notebook project visualizes 3D unit cells and highlights only those cells that contain atoms. The core logic efficiently checks for atom presence within the bounds of a unit cell and uses face-based rendering to distinguish active cells.

---

## 🛠 Tech Stack

| Component         | Description                                           |
|------------------|-------------------------------------------------------|
| Python 3.8+       | Core programming language                            |
| NumPy             | Efficient numerical computation for coordinate logic |
| Matplotlib (3D)   | 3D plotting via `mpl_toolkits.mplot3d`               |
| Jupyter Notebook  | Interactive environment for visualization & testing  |

---

## 📌 Functional Highlights

- **Modular Functions**:
  - `draw_unit_cells_with_atoms`: Renders 3D unit cubes with colored faces.
  - Atom presence detection via bounding logic.
  
- **3D Plotting Features**:
  - Uses `Poly3DCollection` for rendering cube faces.
  - Axes scaling, labels, and viewing angles can be customized.
  
- **Extensible Design**:
  - Ready for integration with simulation data.
  - Can be extended for dislocation visualization, slip system mapping, etc.

---

---

## 🔍 Features

- 🧱 Visualize 3D unit cells in a lattice.
- ⚛️ Highlight and render only those cells that contain atoms.
- 🎨 Colored face rendering for enhanced clarity.
- 🔁 Configurable cell range and atomic position input.
- 💻 Easy-to-run Jupyter Notebook with a clear interface.

---



## 🧪 How It Works

1. The script takes a list of 3D points (atomic positions).
2. It defines a 3D lattice using unit cubes.
3. Each unit cell is checked for atom presence.
4. Only unit cells containing atoms are rendered.
5. Faces of such cells are rendered with customizable colors.

---



### Installation

```bash
git clone https://github.com/yourusername/Crystal-Plasticity-GUI.git
cd Crystal-Plasticity-GUI
pip install -r requirements.txt
