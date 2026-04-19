# 🧍‍♂️ 3D Human Skeleton Reconstruction from Multi‑View Cameras  
### Computer Vision — A.Y. 2025/2026  
### University of Trento

---

## 📌 Overview

This project implements a **3D human skeleton reconstruction pipeline** using the **VolHuMe** multi‑camera RGB dataset.

---

## 🎯 Objectives and Requirements

### 1) 2D Keypoint Annotation
**Goal:** Annotate human keypoints for each camera view.

**Requirements:**
- Annotate 2D human keypoints for every camera.
- Use **Roboflow**:
  - Register one account per group.
  - Email the tutor to be added to the workspace.
- Annotate **at least one complete action**.

---

### 2) 3D Skeleton Triangulation
**Goal:** Triangulate visible joints to obtain a 3D skeleton.

**Requirements:**
- Use multiview 2D annotations.
- Apply triangulation to reconstruct 3D joint positions.
- Visualize the 3D pose.

---

### 2a) Missing / Occluded Joint Reconstruction
**Goal:** Recover joints not visible in some cameras.

**Requirements:**
- Implement your own reconstruction method.
- Combine information from multiple views.
- Enforce skeleton consistency constraints.

---

### 3) Reconstruction Accuracy Evaluation
**Goal:** Measure how accurate the 3D reconstruction is.

**Requirements:**
- Reproject the 3D skeleton back into each camera view.
- Compute:
  - **MPJPE** (Mean Per Joint Position Error)
  - **MSE** (Mean Square Error)
- Evaluate error **only on visible joints**.

---

### 3a) Occlusion Effect Analysis
**Goal:** Study how partial visibility affects reconstruction accuracy.

**Requirements:**
- Analyze error when a joint is:
  - Visible in few cameras.
  - Totally occluded.
  - Estimated using subsets of cameras.

---

### 4) (Bonus) Unreal Engine Visualization
**Goal:** Display the reconstructed 3D skeleton in Unreal Engine.

**Requirements:**
- Import 3D skeleton data.
- Visualize the skeleton.
- Contact the tutor for technical details.

---

## 👥 Team
- **Gianluca Rota** — gianluca.rota@studenti.unitn.it  
- **Diego Mura** — diego.mura@studenti.unitn.it 

---
