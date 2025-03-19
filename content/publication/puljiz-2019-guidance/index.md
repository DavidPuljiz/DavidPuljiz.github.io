---
title: General Hand Guidance Framework using Microsoft HoloLens
authors:
- David Puljiz
- Erik Stöhr
- Katharina S. Riesterer
- Björn Hein
- Torsten Kröger
date: '2019-01-01'
abstract: Hand guidance emerged from the safety requirements for collaborative robots, namely possessing joint-torque sensors. Since then it has proven to be a powerful tool for easy trajectory programming, allowing lay-users to reprogram robots intuitively. Going beyond, a robot can learn tasks by user demonstrations through kinesthetic teaching, enabling robots to generalise tasks and further reducing the need for reprogramming. However, hand guidance is still mostly relegated to collaborative robots. Here we propose a method that does not require any sensors on the robot or in the robot cell, by using a Microsoft HoloLens augmented reality head mounted display. We reference the robot using a registration algorithm to match the robot model to the spatial mesh. The in-built hand tracking and localisation capabilities are then used to calculate the position of the hands relative to the robot. By decomposing the hand movements into orthogonal rotations and propagating it down through the kinematic chain, we achieve a generalised hand guidance without the need to build a dynamic model of the robot itself. We tested our approach on a commonly used industrial manipulator, the KUKA KR-5.
publishDate: '2025-03-07T08:06:47.455460Z'
publication_types:
- paper-conference
publication: '*2019 IEEE/RSJ International Conference on Intelligent Robots and Systems
  (IROS)*'
doi: 10.1109/IROS40897.2019.8967649
tags:
- Augmented Reality
- Robot Programming
- Robot Control
- Human-Robot Interaction
- Computer Vision
- Tracking
- HoloLens 1
- KUKA
- Depth Sensor

featured: true
---
{{< youtube 8Y9Q7bZFGpk >}}