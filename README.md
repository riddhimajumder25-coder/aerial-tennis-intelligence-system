# Aerial Tennis Intelligence System (ATIS)

An engineering project focused on developing a drone-based computer vision system capable of analyzing tennis matches from an aerial perspective.

## Overview

The goal of this project is to create a low-cost tennis analysis platform that combines computer vision, drone technology, and software engineering to provide automated officiating and tactical feedback.

The project is inspired by professional technologies such as Hawk-Eye while remaining realistic and accessible using consumer hardware and open-source software.

---

## Project Goals

### Competitive Mode
- Detect court boundaries
- Track the tennis ball
- Detect bounce locations
- Determine whether shots are IN or OUT
- Automatically keep score
- Generate replay clips

### Practice Mode
- Track player movement
- Analyze court positioning
- Measure recovery after each shot
- Generate tactical feedback
- Visualize movement heatmaps
- Identify shot placement patterns

---

## Technology Stack

### Programming
- Python

### Computer Vision
- OpenCV
- NumPy

### Machine Learning (Future)
- YOLO
- MediaPipe
- PyTorch

### Mobile Development (Future)
- Flutter

### Hardware
- Consumer drone
- Future custom drone platform

---

## Development Roadmap

### Phase 1 — Proof of Concept
- [ ] Load tennis match footage
- [ ] Detect court boundaries
- [ ] Track tennis ball
- [ ] Detect bounce point
- [ ] Determine IN or OUT

---

### Phase 2 — Vision Improvements
- [ ] Improve ball tracking accuracy
- [ ] Improve bounce detection
- [ ] Court coordinate mapping
- [ ] Visualization overlays

---

### Phase 3 — Drone Integration
- [ ] Capture aerial footage
- [ ] Camera stabilization
- [ ] Process drone footage
- [ ] Test on outdoor courts

---

### Phase 4 — Competitive Mode
- [ ] Automatic line calls
- [ ] Score tracking
- [ ] Match statistics
- [ ] Replay generation

---

### Phase 5 — Practice Mode
- [ ] Player tracking
- [ ] Position analysis
- [ ] Recovery analysis
- [ ] Tactical recommendations
- [ ] Heatmaps

---

### Phase 6 — Mobile Application
- [ ] Build mobile app
- [ ] Live match dashboard
- [ ] Session history
- [ ] Statistics visualization

---

## Challenges

This project explores several difficult engineering problems, including:

- Small object tracking
- Camera calibration
- Drone stabilization
- Court detection
- Perspective correction
- Real-time computer vision
- Mobile application development

The goal is not to replicate commercial systems exactly, but to design a functional prototype that demonstrates the integration of mechanical engineering, robotics, computer vision, and software engineering.

---

## Repository Structure

```
aerial-tennis-intelligence-system/

├── docs/
│   ├── research/
│   ├── design/
│   └── diagrams/
│
├── src/
│   ├── court_detection/
│   ├── ball_tracking/
│   ├── player_tracking/
│   ├── bounce_detection/
│   ├── scoring/
│   └── ui/
│
├── tests/
│
├── data/
│   ├── videos/
│   └── sample_frames/
│
├── app/
│
├── drone/
│
├── notebooks/
│
├── README.md
└── requirements.txt
```

---

## Current Status

🚧 Planning & Research

The project is currently in the architecture and research phase. Initial work focuses on understanding tennis court geometry, computer vision techniques, and system design before implementing individual modules.

---

## Author

Riddhi Majumder

Future Mechanical Engineering / Mechatronics Student

Toronto, Canada
