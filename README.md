# esdf_mapper_demo

> Efficient ESDF Mapping from Voxelized Sensor Input

This repository implements a lightweight, CPU-friendly Euclidean Signed Distance Field (ESDF) construction pipeline inspired by [Voxblox](https://github.com/ethz-asl/voxblox), tailored for academic benchmarking and algorithm prototyping in autonomous navigation contexts.

It simulates real-time occupancy grid generation and ESDF propagation on 2.5D slices, supporting modular integration into higher-level planning frameworks such as A*, RRT*, or kinodynamic sampling-based methods.

## ✨ Features

- Minimalistic 3D voxel map representation with efficient memory layout
- Modular architecture for ESDF update cycles and obstacle injection
- Visualization via `numpy` + `PIL` to render signed distance field slices
- Designed for fast prototyping, supports batch experiments for distance transform accuracy

## 📌 Applications

- Autonomous ground/aerial robotics (as mapping front-end)
- Validation of ESDF-based planning algorithms under voxel constraints
- Teaching, research, or interview demonstration of spatial map construction

## 🛠️ Installation

```bash
pip install -r requirements.txt
