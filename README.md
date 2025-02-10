# 🚁 Tello Drone Human Tracking System

An advanced computer vision system that enables DJI Tello drones to detect and autonomously track humans using YOLOv8 and DeepSORT.

## ✨ Key Features

- **Dual Control Modes**
  - 🎮 Manual Mode (Mode 0): Full keyboard-based flight control
  - 🎯 Auto-Tracking Mode (Mode 1): Autonomous human detection and tracking

- **Smart Target Management**
  - Multiple human detection support
  - Dynamic target switching capabilities
  - Interactive target selection interface

- **Video Recording**
  - Automatic video capture in `.avi` format
  - Real-time visual feedback

## 🎮 Controls

### Common Controls
| Key | Action |
|-----|--------|
| T | Take off |
| L | Land |
| V | Toggle video recording |
| M | Switch mode |

### Mode-Specific Controls
#### Manual Mode (0)
| Key | Movement |
|-----|----------|
| W/S | Up/Down |
| A/D | Rotate CCW/CW |
| ←/→ | Left/Right |
| ↑/↓ | Forward/Backward |

#### Tracking Mode (1)
| Key | Action |
|-----|--------|
| C | Toggle target selection |
| ←/→ | Navigate targets |
| Enter | Confirm target |

## 🚀 Quick Start

```bash
python main.py [-h] [-vsize VSIZE] [-th TH] [-tv TV] [-td TD] [-tr TR]
```

### Requirements

- Download Anaconda and create an environment using command line list in requirement.txt or create similar environment using other ways (can refer environment.yml)
- DJI Tello drone

### Reference

1. https://github.com/fvilmos/tello_object_tracking
2. https://github.com/damiafuentes/DJITelloPy
3. https://github.com/ultralytics/ultralytics
4. https://github.com/nwojke/deep_sort
5. https://github.com/computervisioneng/object-tracking-yolov8-deep-sort
6. ChatGPT

