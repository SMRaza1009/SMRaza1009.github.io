---
title: "3D Pose Estimation and Avatar Generation"
date: 2025-02-01
group: "Research Projects"
show: true
---

Developed a 3D human pose estimation pipeline for avatar generation using monocular RGB input.

Employed 2D pose and object detection models to extract joint keypoints and structural cues from video frames.

Lifted 2D predictions into 3D space via RGB-based depth reasoning and point projection to generate coarse 3D meshes.

Applied human motion and texture modeling techniques to generate temporally consistent 3D avatars suitable for visualization and animation tasks.

### Results

<div class="row g-3 mt-2">
  <div class="col-md-4">
    <img src="{{ '/assets/images/projects/3d_avatar/result1.png' | relative_url }}" class="img-fluid rounded border" alt="3D avatar result 1">
  </div>
  <div class="col-md-4">
    <img src="{{ '/assets/images/projects/3d_avatar/result2.png' | relative_url }}" class="img-fluid rounded border" alt="3D avatar result 2">
  </div>
  <div class="col-md-4">
    <img src="{{ '/assets/images/projects/3d_avatar/result3.png' | relative_url }}" class="img-fluid rounded border" alt="3D avatar result 3">
  </div>
</div>
