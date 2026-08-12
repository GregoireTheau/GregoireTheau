# Hi, I'm Grégoire 👋

Graduate from **CentraleSupélec** | Apprentice at **Airbus AI Research**

I work at the intersection of **Trustworthy Computer Vision**, **Geometric Robustness**, and **Certifiable Perception** for safety-critical autonomous systems across **Aerospace, Defense, Drones, and Autonomous Driving**.

---

### Research Focus & Technical Scope

My research focuses on evaluating and validating the operational safety of multi-stage perception chains — bridging keypoint regression networks (e.g., YOLOv8-Pose, YOLO-NAS) with non-linear geometric solvers (Perspective-n-Point) under physically plausible operational conditions:
* **Geometric & Spatial Robustness**: Evaluating perception pipelines against non-convex physical transformations (camera rotation, lighting shifts) beyond standard $L_p$-norm bounded noise.
* **Global Optimization for Verification**: Reformulating pose estimation robustness under **Global Lipschitzian Optimization (GLO)** to systematically isolate critical failure modes and collapse worst-case validation search spaces by over 80%.
* **Vision-Based Navigation & Landing (VBL)**: End-to-end 6-DoF aircraft pose estimation and runway keypoint regression on flight simulation datasets (LARDv2).
* **Differentiable Pose Estimation**: Evaluating backpropagatable PnP formulations (BPnP) as surrogates for gradient-based validation methods.

---

### Selected Repositories & Projects

| Repository | Description | Key Tech / Concepts |
| :--- | :--- | :--- |
| [**geometric-robustness**](https://github.com/GregoireTheau/geometric-robustness) | Robust validation framework for Vision-Based Landing pipelines. Demonstrates the failure of 1st-order gradient attacks (APGD) on multi-stage pose estimation and leverages **Global Lipschitzian Optimization (GLO)** to isolate critical failure modes. | `PyTorch` `YOLOv8-Pose` `BPnP` `GLO/GeoRobust` `LARDv2` |
| [**pnps_comparison**](https://github.com/GregoireTheau/pnps_comparison) | Quantitative benchmark evaluating 5 major Perspective-n-Point formulations (**ITER**, **SQPNP**, **IPPE**, **BPnP**, **P3P**) across 1,000 flight approach scenarios from the LARDv2 dataset under GT and predicted keypoint noise. | `OpenCV` `PyTorch` `PnP Geometry` `Slant Distance Error` |
| [**pose_lardv2**](https://github.com/GregoireTheau/POSE_LARDV2) | A lightweight public starter kit and training pipeline for **YOLO-NAS Pose** on runway corner detection. Designed as an open baseline featuring AWS S3 data streaming (`boto3`), Optuna hyperparameter tuning, and polygon IoU metrics (`shapely`). | `SuperGradients` `YOLO-NAS` `Optuna` `AWS S3` `Shapely` |
| [**ThermiqueSAAS**](https://github.com/GregoireTheau/ThermiqueSAAS) | A SaaS prototype helping roofing professionals estimate thermal gains and heating energy savings for building insulation renovation projects. | `Python` `SaaS` `Web Dev` `Thermal Modeling` |
| [**MultiAgentSystem**](https://github.com/GregoireTheau/MultiAgentSystem) | Academic AI project exploring multi-agent workflows, task orchestration, and Python-based automation. | `Python` `Multi-Agent` `Automation` |

---

### Technical Articles & Publications

* **[Perspective-N-Points (PnP) for Vision-Based Landing (VBL)](https://gregoiretheau.github.io/2026/07/29/pnp-for-vbl.html)**  
  *Deep dive into PnP mathematics, comparing 5 geometric solvers on 1,000 flight approach scenarios from LARDv2 under keypoint noise.*
* **[Synthetic Data Pipeline: Projecting 3D Ground Truth Keypoints to 2D Image Space](https://gregoiretheau.github.io/2026/07/31/ground-truth-3d-to-2d-projection.html)**  
  *Step-by-step breakdown of coordinate frame transformations (ECEF to Camera Optical Frame) for ground-truth validation in flight simulators.*
* One more coming soon ...

---

### Background & Experience

*  **Trustworthy Computer Vision Engineer Apprentice** @ *Airbus AI Research*  
  *Developing robustness evaluation frameworks, failure analysis tools (XAI), and modular pipelines to assess how physical perturbations propagate through safety-critical vision chains.*
*  **Former Air Systems Modeling Apprentice** @ *Dassault Aviation*  
  *Built thermal models for aircraft cabin behavior from large-scale flight test data, validated against physical operational constraints.*
*  **M.S. in AI Engineering** @ *CentraleSupélec*

---

###  Career & Industry Focus

I am looking to apply my expertise in **Trustworthy AI, Robust Computer Vision, and 3D Pose Estimation** to high-stakes autonomous systems across the following sectors:
*  **Defense**: GPS-denied navigation, target detection/tracking, resilient perception under tactical interference.
*  **Unmanned Aerial Systems (UAS / Drones)**: Vision-based navigation, autonomous landing, obstacle avoidance, edge-compute vision.
*  **Aerospace & Avionics**: Certifiable perception, flight automation, optical sensor fusion.
*  **Automotive / Autonomous Vehicles**: Robust perception chains, corner-case validation, physical perturbation testing.

---

###  Tech Stack

**Languages & Frameworks:** `Python` · `PyTorch` · `SuperGradients` · `OpenCV` · `NumPy` · `Pandas`  
**ML & Optimization:** `Deep Learning` · `Computer Vision` · `Keypoint Regression` · `Optuna` · `XAI` · `Robustness Evaluation` · `Scientific ML`  
**Tools & Cloud:** `AWS S3 (boto3)` · `Git` · `LaTeX` · `Shapely` · `TorchMetrics`

---

 **Connect with me:** [LinkedIn](https://www.linkedin.com)
