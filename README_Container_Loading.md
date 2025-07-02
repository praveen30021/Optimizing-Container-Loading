# 📦 Optimizing Container Loading with Heuristics

This project focuses on solving the **container loading problem** using a heuristic-based bin packing algorithm. The goal is to maximize the number of pallets loaded into a standard container (40-foot) while minimizing unused space and avoiding the need for extra containers.

## 📌 Project Overview

- **Objective:** Optimize the arrangement of pallets in a container using packing algorithms.
- **Scenario:** Load a 40-foot container with a mix of:
  - **20 European Pallets** (80 x 120 cm)
  - **4 North American Pallets** (100 x 120 cm)
- **Language & Tools:** Python, `rectpack`, `matplotlib`, `NumPy`, `Pandas`

## 🧠 Core Features

- Modeled pallets as 2D rectangles for container space optimization.
- Used the **`rectpack`** heuristic library for efficient bin packing.
- Compared intuitive vs. optimized strategies for pallet arrangement.
- Visualized container layouts and loading efficiency using `matplotlib`.

## 🔍 Results

| Strategy            | Euro Pallets Loaded | NA Pallets Loaded | Extra Containers Needed |
|---------------------|---------------------|--------------------|--------------------------|
| Intuitive Placement | 20 / 20             | 2 / 4              | ✅ Required              |
| Optimized Packing   | 20 / 20             | 4 / 4              | ❌ Not Required          |

## 📁 Repository Structure

```
├── Optimizing Container Loading.ipynb   # Main notebook with visualization and logic
├── README.md                            # Project overview and usage guide
```

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/container-loading-optimization.git
   cd container-loading-optimization
   ```

2. Install dependencies:
   ```bash
   pip install rectpack matplotlib pandas numpy
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook "Optimizing Container Loading.ipynb"
   ```

## 📌 Future Improvements

- Add 3D packing simulation for real-world use cases.
- Extend to irregular-shaped items or fragile goods.
- Integrate weight balancing constraints per pallet group.

## 🙌 Acknowledgments

Inspired by real-world logistics and supply chain problems, this project applies algorithmic thinking to solve spatial optimization challenges.