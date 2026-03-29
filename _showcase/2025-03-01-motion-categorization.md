---
title: "Motion Categorization using Generative AI Models"
date: 2025-03-01
group: "Research Projects"
show: true
---

Developed a real-time 2D motion categorization framework for sports applications, focusing on dynamic trajectory understanding and prediction.

Generated 2D object tracks and depth maps using off-the-shelf detection and depth estimation models as input to a motion encoder.

Designed a track encoder-decoder architecture that integrates DINO visual features to decouple motion dynamics from semantic appearance.

Utilized SAM2 to group dynamic trajectories belonging to the same object and generate fine-grained moving object masks for improved motion segmentation.

### Results

<div class="row g-3 mt-2">
  <div class="col-md-6">
    <img src="{{ '/assets/images/projects/motion_categorization/result1.png' | relative_url }}" class="img-fluid rounded border" alt="Motion categorization result 1">
  </div>
  <div class="col-md-6">
    <img src="{{ '/assets/images/projects/motion_categorization/result2.png' | relative_url }}" class="img-fluid rounded border" alt="Motion categorization result 2">
  </div>
</div>
