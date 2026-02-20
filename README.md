Real-Time Object Detection Using Hardware-Accelerated CNN on Xilinx Zynq FPGA with Arm Processor
🚀 Project Overview

This project demonstrates deployment of YOLOv5 object detection on a Xilinx Zynq FPGA platform with ARM processor.

The system evaluates CPU-based inference and simulates DPU hardware acceleration to analyze performance improvements in embedded AI applications.

Architecture Image: 


<img width="350" height="350" alt="image" src="https://github.com/user-attachments/assets/689b40cc-cf1d-4fe7-a066-c473a5cec365" />



🧠 Key Features

YOLOv5-based object detection

CPU vs Hardware Acceleration comparison

Performance benchmarking (Latency & FPS)

Embedded deployment workflow

Vitis AI quantization and compilation pipeline



⚙️ Tools & Technologies

Xilinx Zynq-7000 FPGA

Vitis AI

YOLOv5

Python

OpenCV

NumPy

📊 Performance Results

| Mode          | Inference Time | Total Time | FPS  |
| ------------- | -------------- | ---------- | ---- |
| CPU           | 28,954 ms      | 30,912 ms  | 0.03 |
| Simulated DPU | 85 ms          | 2,040 ms   | 0.49 |

