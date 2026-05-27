# Robotic Tentacle Arm : Concept Design

Bio-inspired tendon-driven robotic arm concept with a multi-jointed
end-effector, designed for delicate agricultural produce handling.
Finalist - ANVESHANA'25 National Level Prototype Competition, BMSIT&M.

## Status
🎨 Concept and 3D model phase - physical prototype not yet built.
The current model is a design exploration inspired by biological
tentacle motion. Practical refinements are planned for future iterations.

## Concept

Conventional robotic arms are rigid and struggle with delicate produce.
This design explores a flexible, tendon-driven approach where:
- Multiple segments are actuated by servo motors (TowerPro SG90)
- Tendon-like cables enable fluid, natural motion
- A multi-jointed end-effector handles grasping and repositioning
- A Raspberry Pi camera at the tip enables real-time visual feedback

Inspired by biological tentacle movement and the articulated limbs
of Dr. Octopus — prioritizing flexibility over rigidity.

## 3D Model

| File | Description |
|------|-------------|
| `models/tentacle_arm_with_endeffector.stl` | Full arm with multi-jointed end-effector |

> ⚠️ Current model is a conceptual design. Practical geometry and
> segment sizing will be refined in the next iteration.

## Planned Hardware

| Component | Role |
|-----------|------|
| TowerPro SG90 Servos | Actuate each arm segment via tendons |
| Arduino / Microcontroller | Coordinate servo movements |
| Raspberry Pi + Camera | Real-time visual feedback and object detection |
| PLA / PETG 3D printed parts | Lightweight arm segments |
| Tendon cables | Transmit servo motion along segments |

## Planned Software

- Inverse kinematics for smooth multi-segment motion
- OpenCV-based object detection for produce recognition
- Real-time grip adjustment based on camera feedback

## Future Work

- Refine segment geometry for practical agricultural use
- Build physical prototype with servo-tendon mechanism
- Integrate Raspberry Pi camera with OpenCV
- Field test with delicate produce (fruits, flowers)
- Explore soft robotics materials (silicone, PETG)

## Academic Context

**Concept Project — Electronics & Communication Engineering**
BMS Institute of Technology and Management, Bengaluru
Mentor: Dr. Saneesh Cleatus | 2024–25

## Team

| Name | Role |
|------|------|
| Alan Biju | Mechanical design and hardware |
| Tejashwini S Uranakar | Control algorithms and software |
| Arindam Kashyap | Mechanical design and hardware |

## Award

🏆 Finalist - ANVESHANA'25 National Level Prototype Competition
BMS Institute of Technology and Management, 2025
