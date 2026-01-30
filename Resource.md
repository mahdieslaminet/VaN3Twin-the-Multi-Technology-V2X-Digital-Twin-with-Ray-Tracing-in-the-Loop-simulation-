# 🚀 VaN3Twin — Ultimate V2X & Cooperative Perception Resources Guide (2025 Edition)

This repository compiles the **most comprehensive and up-to-date open-source collection** of resources for **Vehicle-to-Everything (V2X)**, **Cooperative Perception**, **V2V/V2I**, and urban vehicular networks (fully updated as of December 2025).  
It serves as a one-stop guide for researchers, developers, and enthusiasts seeking datasets, tools, simulators, frameworks, and code to benchmark and advance connected and autonomous vehicle systems.

---

## 📊 Resource Overview

| Category                          | Count | Key Highlights                                                                 |
|-----------------------------------|-------|---------------------------------------------------------------------------------|
| Real-World V2X Datasets           | 20+   | Multi-modal real-world data (2024–2025), including 4D Radar, online fusion, multi-intersection scenarios |
| Simulated V2X Datasets            | 12+   | CARLA + SUMO synthesized data with adverse weather & 4D Radar support          |
| General Autonomous Driving Datasets | 15+ | Standard baselines for comparison                                              |
| Simulators & Platforms            | 8+    | Full-stack traffic and V2X simulation tools                                    |
| Frameworks & Libraries            | 15+   | State-of-the-art fusion, evaluation, and cooperative perception models         |
| **Total Resources**               | **90+** | Actively maintained through end of 2025                                        |

---

## 🗂 Real-World V2X Datasets (Updated 2025)

| Name              | Description                                              | Sensors                     | Year / Conference         | Links                                                                 |
|-------------------|----------------------------------------------------------|-----------------------------|---------------------------|-----------------------------------------------------------------------|
| V2X-Real (UCLA)   | Largest real-world multi-vehicle + infrastructure V2X    | LiDAR, Camera              | 2024 / ECCV              | [GitHub](https://github.com/ucla-mobility/V2X-Real) • [Website](https://mobility-lab.seas.ucla.edu/v2x-real/) |
| V2X-ReaLO         | Online real-time dynamic extension of V2X-Real           | LiDAR, Camera              | 2025                     | [arXiv](https://arxiv.org/abs/2503.10034)                            |
| V2V4Real (UCLA)   | Largest real-world V2V multi-modal dataset               | LiDAR, Camera              | 2023 / CVPR              | [GitHub](https://github.com/ucla-mobility/V2V4Real)                  |
| V2X-Radar         | First real-world 4D Radar dataset (rain, night, fog)      | LiDAR, Camera, 4D Radar    | 2025 / NeurIPS Spotlight | [GitHub](https://github.com/yanglei18/V2X-Radar)                     |
| UrbanIng-V2X      | Multi-vehicle & multi-infrastructure urban intersections | LiDAR, Camera              | 2025 / NeurIPS           | [GitHub](https://github.com/thi-ad/UrbanIng-V2X)                     |
| TUMTraf-V2X       | High-quality European dataset with HD maps               | LiDAR, Camera, HD Maps     | 2024 / CVPR              | [Website](https://tum-traffic-dataset.github.io/tumtraf-v2x/)        |
| DAIR-V2X          | Real-world Vehicle-to-Infrastructure                     | LiDAR, Camera              | 2022                     | [GitHub](https://github.com/AIR-THU/DAIR-V2X)                        |
| DAIR-V2X-Seq      | Sequential dataset with cooperative prediction           | LiDAR, Camera              | 2023 / CVPR              | [GitHub](https://github.com/AIR-THU/DAIR-V2X-Seq)                    |
| DOLPHINS          | Multi-view and multi-scenario                            | Camera, LiDAR              | 2023                     | [Website](https://dolphins-dataset.net/)                             |

---

## 🧪 Simulated V2X Datasets

| Name       | Description                                          | Simulator       | Links                                                                 |
|------------|------------------------------------------------------|-----------------|-----------------------------------------------------------------------|
| V2X-Sim    | Classic synthetic collaborative perception dataset   | CARLA + SUMO    | [GitHub](https://github.com/ai4ce/V2X-Sim)                           |
| Multi-V2X  | Multi-modal with variable penetration rates          | CARLA + SUMO    | [GitHub](https://github.com/RadetzkyLi/Multi-V2X)                    |
| V2X-R (sim)| Simulated 4D Radar + adverse weather conditions      | CARLA-based     | [GitHub](https://github.com/ylwhxht/V2X-R)                           |
| OPV2V      | Standard V2V collaborative benchmark                 | CARLA           | Integrated in OpenCOOD                                               |
| V2XSet     | Unified benchmark format                             | CARLA           | Integrated in OpenCOOD                                               |

---

## 📦 Baseline Autonomous Driving Datasets

- **Waymo Open Dataset** → [Website](https://waymo.com/open/download)
- **nuScenes** → [Website](https://www.nuscenes.org)
- **Argoverse 2** → [Website](https://www.argoverse.org)
- **KITTI** → [Website](http://www.cvlibs.net/datasets/kitti)
- **BDD100K** → [Website](https://bdd-data.berkeley.edu)

---

## ⚙️ Simulation Platforms

| Name     | Type                               | Links                                            |
|----------|------------------------------------|--------------------------------------------------|
| CARLA    | Open-source urban driving simulator| [Website](https://carla.org)                     |
| SUMO     | Microscopic traffic simulator      | [Website](https://www.eclipse.org/sumo)          |
| OpenCDA  | Cooperative driving architecture   | [GitHub](https://github.com/OpenAutonomy/OpenCDA)|

---

## 🛠 Frameworks & Libraries

| Name       | Primary Use Case                                      | Links                                                                 |
|------------|-------------------------------------------------------|-----------------------------------------------------------------------|
| OpenCOOD   | Leading cooperative 3D object detection framework (supports most datasets) | [GitHub](https://github.com/OpenCOOD/OpenCOOD)                       |
| V2X-ViT    | Vision Transformer for cooperative perception (ECCV 2022) | [GitHub](https://github.com/DerrickXuNu/v2x-vit)                     |

---
## 🗂 Real-World & Research Datasets

- **V2X-Real (UCLA Mobility Lab)** — First large-scale real-world multi-modal dataset for cooperative perception (vehicles + infrastructure, multi-view cameras + LiDARs).  
  [https://mobility-lab.seas.ucla.edu/v2x-real/](https://mobility-lab.seas.ucla.edu/v2x-real/)

- **UrbanIng-V2X** — Large multi-vehicle, multi-infrastructure dataset with synchronized LiDAR and camera sensors at urban intersections.  
  [https://github.com/thi-ad/UrbanIng-V2X](https://github.com/thi-ad/UrbanIng-V2X)

- **DAIR-V2X (AIR-THU)** — Real-world vehicle-to-infrastructure cooperative dataset.  
  GitHub: [https://github.com/AIR-THU/DAIR-V2X](https://github.com/AIR-THU/DAIR-V2X)

- **DAIR-V2X-Seq** — Sequential dataset with cooperative perception + forecasting (vehicle & infrastructure).  
  GitHub: [https://github.com/AIR-THU/DAIR-V2X-Seq](https://github.com/AIR-THU/DAIR-V2X-Seq)

- **V2V4Real** — Real V2V cooperative perception dataset (benchmarks, multimodal).

- **V2X-Radar** — Multi-modal dataset with 4D radar for cooperative perception.

- **DeepAccident** — Dataset for V2X motion + accident prediction (benchmarks).

- **Adver-City** — V2X collaborative dataset under adverse weather conditions.

- **DOLPHINS Dataset** — Large variety multi-view, multi-scenario V2X collaborative perception dataset with images and point clouds.  
  [https://dolphins-dataset.net/](https://dolphins-dataset.net/)

- **V2AIX** — Real-world ITS V2X messaging dataset (ETSI standardized V2X messages).  
  [https://v2aix.ika.rwth-aachen.de](https://v2aix.ika.rwth-aachen.de)

---

## 📦 Large Autonomous Driving Datasets Useful for V2X Research

- Waymo Open Dataset — [https://waymo.com/open/download](https://waymo.com/open/download)  
- Lyft Level 5 Dataset — [https://level5.lyft.com/dataset/](https://level5.lyft.com/dataset/)  
- nuScenes — [https://www.nuscenes.org](https://www.nuscenes.org)  
- Argoverse 1 & 2 — [https://www.argoverse.org](https://www.argoverse.org)  
- KITTI Vision Benchmark — [http://www.cvlibs.net/datasets/kitti](http://www.cvlibs.net/datasets/kitti)  
- Cityscapes — [https://www.cityscapes-dataset.com](https://www.cityscapes-dataset.com)  
- BDD100K — [https://bdd-data.berkeley.edu](https://bdd-data.berkeley.edu)  
- Audi A2D2 — [https://www.a2d2dataset.org](https://www.a2d2dataset.org)  
- Mapillary Vistas — [https://www.mapillary.com/dataset/vistas](https://www.mapillary.com/dataset/vistas)  
- ApolloScape — [http://apolloscape.auto](http://apolloscape.auto)  
- Comma.ai (comma2k19) — [https://github.com/commaai/comma2k19](https://github.com/commaai/comma2k19)  
- HighD Dataset — [https://highd-dataset.com](https://highd-dataset.com)  
- TrajNet++ / TrajNet — [https://trajnet.github.io](https://trajnet.github.io)  
- Oxford RobotCar — [http://robotcar-dataset.robots.ox.ac.uk](http://robotcar-dataset.robots.ox.ac.uk)

---

## 🛠 Simulation & Tool Datasets / Environments

- CARLA Simulator — [https://carla.org](https://carla.org)  
- SUMO Traffic Simulator — [https://www.eclipse.org/sumo](https://www.eclipse.org/sumo)  
- LGSVL Simulator — [https://www.lgsvlsimulator.com](https://www.lgsvlsimulator.com)  
- OpenAutonomy & OpenCDA — [https://github.com/OpenAutonomy/OpenCDA](https://github.com/OpenAutonomy/OpenCDA)  
- Apollo Autonomous Driving Platform — [https://github.com/ApolloAuto/apollo](https://github.com/ApolloAuto/apollo)  
- CoAlign — [https://github.com/yifanlu0227/CoAlign](https://github.com/yifanlu0227/CoAlign)

---

## 🚀 Papers with Code / Model Implementations (V2X)

- Cooperative Perception Surveys & Digests  
- V2X-ViT implementation  
- V2VNet baseline (OpenCOOD)  
- F-Cooper (cooperative detection)  
- Attentive Fusion (baseline fusion method)  
- MASH / DiscoNet (collaborative perception models)  
- Sensor Fusion Benchmarks (Radar + LiDAR + Camera)  
- Weather-condition perception models  
- Temporal Forecasting Tasks (V2X-Seq)  
- 4D Radar Cooperative Perception Models

---

## 📚 V2X / Cooperative Perception Datasets & Resources

### Major Datasets & Repos
- **V2X-Real** (UCLA Mobility Lab) — https://github.com/ucla-mobility/V2X-Real  
- **Multi-V2X** — https://github.com/RadetzkyLi/Multi-V2X  
- **DAIR-V2X** — https://github.com/AIR-THU/DAIR-V2X  
- **V2X-Sim** — https://github.com/ai4ce/V2X-Sim  
- **OpenCOOD (OPV2V, V2XSet)** — https://github.com/DerrickXuNu/OpenCOOD  
- **V2V4Real, TUMTraf-V2X, V2X-Radar** — real-world benchmarks  

### Classic AV Datasets (Useful for Baselines)
- Waymo Open — https://waymo.com/open/download  
- nuScenes — https://www.nuscenes.org  
- Argoverse — https://www.argoverse.org  
- KITTI — http://www.cvlibs.net/datasets/kitti  
- Audi A2D2 — https://www.a2d2dataset.org

## 🚀 Quick Start Guide

1. **Install (Recommended)**  
```bash
git clone https://github.com/M-Amin-Wolverine/VaN3Twin-the-Multi-Technology-V2X-Digital-Twin-with-Ray-Tracing-in-the-Loop-/
cd VaN3Twin-the-Multi-Technology-V2X-Digital-Twin-with-Ray-Tracing-in-the-Loop-
pip install -r requirements.txt
```

🎥 **Top exapmples**

**V2X Cooperative Perception - Bird's Eye View Fusion**  
![V2X-ViT BEV Fusion](https://raw.githubusercontent.com/DerrickXuNu/v2x-vit/main/assets/v2xvit_framework.png)  
![CoBEVT Example](https://raw.githubusercontent.com/DerrickXuNu/CoBEVT/main/assets/cobevt.png)

**CARLA + V2X-Sim Multi-Vehicle Scenario**  
![V2X-Sim Scenario](https://raw.githubusercontent.com/ai4ce/V2X-Sim/master/docs/images/v2xsim_scenario.jpg)  
![V2X-Sim Data Example](https://raw.githubusercontent.com/ai4ce/V2X-Sim/master/docs/images/data_example.png)

**4D Radar Point Cloud in Adverse Weather (V2X-Radar Dataset)**  
![V2X-Radar Adverse Weather](https://raw.githubusercontent.com/yanglei18/V2X-Radar/main/assets/radar_adverse.png)  
![V2X-Radar Point Cloud](https://raw.githubusercontent.com/ylwhxht/V2X-R/master/assets/v2xr_weather.png)

**Real-World V2X-Real Dataset Sample (UCLA)**  
![V2X-Real Sample](https://raw.githubusercontent.com/ucla-mobility/V2X-Real/main/assets/v2xreal_example.jpg)  
![V2X-Real Multi-View](https://raw.githubusercontent.com/ucla-mobility/V2X-Real/main/assets/v2xreal_multiview.png)

**Cooperative 3D Object Detection Results (OpenCOOD)**  
![OpenCOOD Detection Results](https://raw.githubusercontent.com/DerrickXuNu/OpenCOOD/main/docs/images/opencood_results.png)  
![OpenCOOD Visualization](https://raw.githubusercontent.com/DerrickXuNu/OpenCOOD/main/assets/vis_example.gif)

**Infrastructure-to-Vehicle Perception (DAIR-V2X)**  
![DAIR-V2X I2V](https://raw.githubusercontent.com/AIR-THU/DAIR-V2X/main/docs/images/dairv2x_i2v.png)  
![DAIR-V2X Fusion](https://raw.githubusercontent.com/AIR-THU/DAIR-V2X/main/docs/images/vic3d_example.jpg)


⚠️ **Best Practices & Notes**

- **Licenses & Citations**: Always cite related papers and check dataset licenses.
- **Privacy**: Real-world datasets may contain sensitive information.
- **Benchmarking**: Use standard metrics (mAP, NDS) and official train/val/test splits.

🤝 **Contributions**  
This list is continuously updated. To add new resources:

- Fork the repo
- Submit a Pull Request or open an Issue

📞 **Contact & Resources**

- 📧 Email: Amin.khodadadi006@gmail.com
- 💻 Main GitHub Repository: VaN3Twin
- 🌐 OpenStreetMap Integration: https://www.openstreetmap.org
- 📂 Google Drive (datasets & simulations): [Your Link Here]
- 🖥️ Google Colab (online simulations): [Your Link Here]

🙏 **Acknowledgements**  
This project is supervised by: Dr. Mehdi Eslami – Associate Professor, Islamic Azad University, Science and Research Branch, Tehran, Iran  
📧 Email: mehdi.eslami@iausr.ac.ir  

We sincerely thank Dr. Eslami for his guidance and support.

📄 **Citation**

```bibtex
@misc{van3twin-v2x-resources-2025,
  title = {VaN3Twin V2X Research Resources \& Dataset Guide (2025 Edition)},
  author = {M. Amin Khodadadi and Community Contributors},
  year = {2025},
  howpublished = {\url{https://github.com/M-Amin-Wolverine/VaN3Twin-the-Multi-Technology-V2X-Digital-Twin-with-Ray-Tracing-in-the-Loop-/}},
  note = {Comprehensive and up-to-date collection of V2X and Cooperative Perception resources}
}
