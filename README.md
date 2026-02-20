🚀 Project Overview

This project demonstrates real-time object detection using YOLOv5 deployed on the PYNQ-Z2 board (Zynq-7000 SoC) featuring an ARM Cortex-A9 processor and FPGA fabric.

The system evaluates:

CPU-based inference on ARM processor

Simulated / Hardware-accelerated inference (DPU concept)

Performance comparison (Latency & FPS)

This project highlights how FPGA-based acceleration improves embedded AI performance.


Architecture Image: 


<img width="350" height="350" alt="image" src="https://github.com/user-attachments/assets/689b40cc-cf1d-4fe7-a066-c473a5cec365" />



🧠 Key Features

YOLOv5-based object detection

Deployment on PYNQ-Z2 FPGA Board

CPU vs Hardware Acceleration comparison

Performance benchmarking (Inference Time & FPS)

Embedded AI workflow

Vitis AI quantization and compilation pipeline

Jupyter Notebook based implementation




🧰 Tools & Technologies

PYNQ-Z2 FPGA Board

Vitis AI

YOLOv5

Python

OpenCV

NumPy

Jupyter Notebook



📊 Performance Results

| Mode          | Inference Time | Total Time | FPS  |
| ------------- | -------------- | ---------- | ---- |
| CPU           | 28,954 ms      | 30,912 ms  | 0.03 |
| Simulated DPU | 85 ms          | 2,040 ms   | 0.49 |

