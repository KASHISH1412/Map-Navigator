# 📍 Map Navigator and Route Optimization Tool

## 📝 Project Summary
This system offers a robust and flexible solution for navigating maps and optimizing routes. It includes:
- A **Graphical User Interface (GUI)** for interactive use.
- A **console-based engine** for batch processing and integration into other systems.

Efficient pathfinding is achieved through advanced data structures like **Fibonacci Heaps** and optimized algorithms for route computation.

---

## 🔧 Components

### 1. `GUI.py` – Graphical User Interface
- Built using the **Kivy** framework for cross-platform compatibility.
- Enables users to:
  - 📂 Select map and query files.
  - 🧭 View and interact with computed routes.
  - 📊 See detailed route information.
- Features:
  - File pickers
  - Action buttons (e.g., "Execute All")
  - Visual map rendering

### 2. `FibHeap.py` – Fibonacci Heap Implementation
- Custom implementation of **Fibonacci Heap**, crucial for efficient priority queue handling in pathfinding.
- Supports operations such as:
  - `insert`
  - `extract_min`
  - `decrease_key`
  - `merge`
- Maintains performance with:
  - Cascading cuts
  - Heap consolidation

---

## ▶️ How to Use

### 🖥️ GUI Mode
1. Run `GUI.py`.
2. Use the GUI controls to:
   - Load a map file.
   - Load a query file.
   - View route visualization.
3. Click **"Execute All"** to process multiple queries in a batch.

### 💻 Console Mode
- Import and use the routing algorithms in any Python script or terminal.
- Ensure:
  - Valid file paths.
  - Proper input formatting (for maps and queries).

---

## 📦 Dependencies

Install the following Python packages:

```bash
pip install kivy==2.2.1 matplotlib==3.8.2 tqdm==4.66.1
