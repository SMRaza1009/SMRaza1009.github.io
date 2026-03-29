---
title: "3D Mesh Simplification and Compression Analysis"
date: 2025-04-01
group: "Projects"
show: true
width: 12
---

Developed an automated pipeline for 3D mesh simplification and compression analysis across multiple decimation levels.

Implemented a Python–Open3D framework to batch-process polygonal meshes (OBJ/PLY/STL/OFF) using quadric-error-based decimation at varying target triangle ratios.

Designed evaluation metrics to quantify compression–quality trade-offs, including vertex and triangle reduction, file size compression ratio, and approximate Chamfer distance.

Built an automated reporting system exporting per-model JSON summaries, enabling efficient comparison of geometric distortion across simplification levels.

Optimized mesh preprocessing with degenerate triangle removal and normal recomputation, improving robustness for large-scale mesh datasets.
