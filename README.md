# Thumb CMC Arthroplasty – Biomechanical Data Pipeline

A Python data processing pipeline developed in collaboration with The Ottawa Hospital and the Division of Orthopaedic Surgery to analyze cadaveric biomechanical data.

## Overview
This project supports clinical research on optimal surgical cup positioning for thumb CMC arthroplasty.

## Features
- Processes data from 8 cadaveric specimens across 15 cup orientations and 8 thumb movements
- Extracts range of motion (ROM) limits using hierarchical stopping criteria (torque rate drop, translation thresholds, resultant torque)
- Iterative threshold calibration with visual validation
- Generates per-specimen and average ROM tables (mean ± SD)

## Tech Stack
- **Language:** Python
- **Libraries:** NumPy, Pandas, Matplotlib
- **Data sources:** KUKA 6-axis robot, OptiTrack motion capture, force/torque sensors

## Clinical Impact
Results support data-driven decision-making for optimal implant positioning.
