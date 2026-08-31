# Hi, I'm Grégoire 👋

**Computer Vision & Autonomous Systems Engineer** from CentraleSupélec, currently working at **Airbus AI Research**.

I build and evaluate perception systems for safety-critical autonomous applications, with a focus on **3D pose estimation, vision-based navigation, geometric computer vision, and robustness**.

My current work focuses on end-to-end validation of **Vision-Based Landing** pipelines, from runway keypoint detection to **6-DoF pose estimation**, under physically plausible geometric and photometric perturbations.

---

## Featured Projects

### [geometric-robustness](https://github.com/GregoireTheau/geometric-robustness)

**📄 Publication :** [*Robust Validation to Geometric Perturbations for Autonomous Pose Estimation*](https://arxiv.org/abs/2608.21066)

Robustness evaluation framework for Vision-Based Landing pipelines combining **YOLOv8-Pose** keypoint detection and **PnP-based 6-DoF pose estimation**.

Benchmarks gradient-based attacks, random search, and derivative-free global optimization under geometric perturbations. Global search exposed critical pose-estimation failures exceeding **1,000 m** and reduced the retained search-space volume by **over 80% after 10 iterations**.

`PyTorch` · `YOLOv8-Pose` · `PnP` · `BPnP` · `GeoRobust` · `LARDv2`

---

### [pnps_comparison](https://github.com/GregoireTheau/pnps_comparison)

Quantitative benchmark of **5 Perspective-n-Point solvers** across **1,000 simulated aircraft approaches**, evaluating how keypoint localization errors propagate into 6-DoF pose estimation.

`OpenCV` · `PyTorch` · `PnP` · `3D Geometry` · `Pose Estimation`

---

### [POSE_LARDV2](https://github.com/GregoireTheau/POSE_LARDV2)

End-to-end training and evaluation pipeline for **runway keypoint detection** using YOLO-NAS Pose, including hyperparameter optimization, cloud-based data access, and custom geometric evaluation metrics.

`YOLO-NAS Pose` · `SuperGradients` · `Optuna` · `AWS S3` · `Shapely`

---

## Technical Writing

- **[Perspective-n-Point for Vision-Based Landing](https://gregoiretheau.github.io/2026/07/29/pnp-for-vbl.html)**  
  Deep dive into PnP geometry and a comparison of 5 solvers across 1,000 simulated aircraft approaches under keypoint noise.

- **[Projecting 3D Ground Truth Keypoints to 2D Image Space](https://gregoiretheau.github.io/2026/07/31/ground-truth-3d-to-2d-projection.html)**  
  Step-by-step breakdown of coordinate-frame transformations for projecting 3D runway landmarks into the camera image plane.

---

## Experience

### Airbus AI Research
**Computer Vision & AI Robustness Engineer — Apprenticeship**

Working on robustness and V&V for Vision-Based Landing systems:

- End-to-end perception-to-pose pipelines
- Runway keypoint detection
- Perspective-n-Point pose estimation
- Physically plausible perturbation testing
- Black-box and differentiable robustness evaluation

### Dassault Aviation
**Air Systems Modelling Engineer — Apprenticeship**

Developed **physics-based thermal models** of aircraft cabin dynamics from flight-test measurements, digital mock-up data, material properties, and thermal exchange mechanisms to support Falcon 10X control-law design.

### CentraleSupélec
**M.S. in Engineering — Artificial Intelligence**

Computer Vision · Deep Learning · Reinforcement Learning · Optimization

---

## Technical Stack

**Computer Vision & Geometry**  
`3D Pose Estimation` · `PnP` · `Keypoint Detection` · `Object Detection` · `Geometric Computer Vision`

**Machine Learning**  
`PyTorch` · `Deep Learning` · `Robustness Evaluation` · `Global Optimization` · `Explainability`

**Engineering**  
`Python` · `OpenCV` · `NumPy` · `SciPy` · `Pandas` · `Git` · `AWS`

---

## Connect

[LinkedIn](https://www.linkedin.com/in/gregoire-theau) · [GitHub](https://github.com/GregoireTheau)
