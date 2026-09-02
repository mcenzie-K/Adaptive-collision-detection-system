# Adaptive-collision-detection-system
# SIH26037 — Adaptive Path Planning & Collision Avoidance for Autonomous Vehicles on Unstructured Indian Roads

A prototype demonstrating adaptive path planning and real-time collision avoidance for autonomous vehicles navigating unstructured Indian roads — no lane markings, unpredictable obstacles (potholes, stray cattle, pedestrians), and dynamic traffic patterns.

This simulation validates the core planning logic: a global path is computed using A* around known static obstacles (potholes), and the vehicle dynamically replans in real time when a previously unknown obstacle (pedestrian/cattle) enters its sensor range and blocks the planned route.

Built as part of Smart India Hackathon 2026 (Problem Statement SIH26037, sponsored by MathWorks).

## Demo

[Adaptive Path Planning Demo](./download.gif)

*Red path = original A* plan | Green sensor circle = detection range | Red reroute = real-time replanning after obstacle detection*
