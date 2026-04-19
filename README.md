# 🧍‍♂️ 3D Human Skeleton Reconstruction from Multi‑View Cameras  
### Computer Vision — A.Y. 2025/2026  
### University of Trento

---

## 📌 Overview

This project implements a **3D human skeleton reconstruction pipeline** using the **VolHuMe** multi‑camera RGB dataset.

The main objectives are:
- Annotate 2D human keypoints from multiple camera views.
    Requirements:
        a) Annotate human keypoint for each camera.
        b) Use Roboflow.
            b.1) register to **Roboflow** (one account per group)
            b.2) send to the tutor one email per group to be added to Roboflow
        c) Annotate at least one complete action
- Triangulate visible joints to obtain a 3D skeleton.
    Requirements:
        a) Annotate 2D multiview.
        b) Triangulate visible joints to obtain a 3D skeleton.
        c) Visualize 3D pose.
- Reconstruct missing or occluded joints (How can we reconstruct missing or occluded joints by combining information from multiple views and enforcing skeleton consistency?).
    Requirements:
        a) Implement own method.
- Evaluate reconstruction accuracy via reprojection error.
    Requirements:
        a) Apply skelethon reprojection 3D onto 2D images. 
        b) Compute loss function such as MPJPE (mean per joint position error) and mean square error.
- Occlusions Effect
    Requirements:
        a) Analyze Error Changing when a joint is:
            a.1) visible in a few cameras.
            a.2) totally occluded
            a.3) when we use cameras subset.
- (Bonus) Visualize the 3D skeleton in Unreal Engine.
    Requirements:
        a) 3D importing.
        b) Skelethon visualization.
        c) Contact tutor for technical details.
---

## 👥 Team
- **Gianluca Rota** — gianluca.rota@studenti.unitn.it  
- **Diego Mura** — diego.mura@studenti.unitn.it 

---
