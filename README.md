# Unifying Visual SLAM

A curated list of resources to help unify and standardize the landscape of Visual SLAM, Structure-from-Motion, datasets, tools, and educational content. This page collects links to key projects, foundational papers, tools, and talks.

This collection was created as an outcome of the RSS 2025 Workshop [Unifying Visual SLAM](https://visual-slam-lab.github.io/unifying-visual-slam/). Organizers: <a href="https://scholar.google.com/citations?user=SDtnGogAAAAJ&hl=en"><strong>Alejandro Fontan</strong></a>, <a href="https://schmluk.github.io"/><strong>Lukas Schmid</strong></a>, <a href="https://cvg.ethz.ch/team/Dr-Olga-Vysotska"/><strong>Olga Vysotska</strong></a>, <a href="https://www.linkedin.com/in/mubarizzaffar/"><strong>Mubariz Zaffar</strong></a>,  <a href="https://lpanaf.github.io/"><strong>Linfei Pan</strong></a>, <a href="https://gokulbnr.github.io/"><strong>Gokul B. Nair</strong></a>,  <a href="https://scholars.uow.edu.au/johan-barthelemy"><strong>Johan Barthelemy</strong></a>, <a href="https://scholar.google.com/citations?user=j_sMzokAAAAJ&hl=en"><strong>Javier Civera</strong></a> and <a href="https://scholar.google.com/citations?user=TDSmCKgAAAAJ&hl=en"><strong>Michael Milford</strong></a>

👋 **Contributions are welcome!**! Feel free to open an issue or submit a pull request to suggest more tools, papers, or resources.

---

## 📌 Contents

- [Visual SLAM](#visual-slam)
- [Benchmarks / Libraries](#benchmarks--libraries)
- [Foundational Datasets](#foundational-datasets)
- [Foundational Papers](#foundational-papers)
- [Educational Resources](#educational-resources)
- [Datasets](#datasets)
- [Structure-from-Motion (SfM)](#structure-from-motion-sfm)
- [Talks](#talks)
- [Other Tools](#other-tools)
- [More Resources](#more-resources)

---

<details open>
<summary><strong>Visual SLAM</strong></summary>

| Link | Description |
|------|-------------|
| [MASt3R-SLAM](https://edexheim.github.io/mast3r-slam/) | Real-Time Dense SLAM with 3D Reconstruction Priors |
| [MonoGS](https://rmurai.co.uk/projects/GaussianSplattingSLAM/) | Gaussian Splatting SLAM |
| [DPVO](https://github.com/princeton-vl/DPVO) | Deep Patch Visual Odometry/SLAM |
| [DROID-SLAM](https://github.com/princeton-vl/DROID-SLAM) | Deep Visual SLAM for Monocular, Stereo, and RGB-D Cameras |
| [ORB-SLAM2](https://github.com/raulmur/ORB_SLAM2) | SLAM for Monocular, Stereo, and RGB-D Cameras |
| [DSO](https://github.com/JakobEngel/dso) | Direct Sparse Odometry |

</details>

<details>
<summary><strong>Benchmarks / Libraries</strong></summary>

| Link | Description |
|------|-------------|
| [VSLAM-LAB](https://github.com/alejandrofontan/VSLAM-LAB) | A Comprehensive Framework for Visual SLAM Baselines and Datasets |
| [VPR-methods](https://github.com/gmberton/VPR-methods-evaluation) | VPR Methods Evaluation |
| [PySLAM](https://github.com/luigifreda/pyslam) | Python SLAM pipeline for monocular, stereo and RGB-D |
| [slamplay](https://github.com/luigifreda/slamplay) | C++ SLAM experimentation tools |

</details>

<details>
<summary><strong>Foundational Datasets</strong></summary>

| Link | Description |
|------|-------------|
| [ETH3D](https://www.eth3d.net/slam_datasets) | ETH3D SLAM & Stereo Benchmarks |
| [RGB-D TUM](https://cvg.cit.tum.de/data/datasets/rgbd-dataset) | RGB-D SLAM Dataset and Benchmark |

</details>

<details>
<summary><strong>Foundational Papers</strong></summary>

| Link | Description |
|------|-------------|
| [PTAM](https://www.robots.ox.ac.uk/~gk/publications/KleinMurray2007ISMAR.pdf) | Parallel Tracking and Mapping for Small AR Workspace |
| [MonoSLAM](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=4160954) | Real-Time Single Camera SLAM |

</details>

<details>
<summary><strong>Educational Resources</strong></summary>

| Link | Description |
|------|-------------|
| [SLAM Handbook](https://github.com/SLAM-Handbook-contributors/slam-handbook-public-release) | SLAM Handbook |
| [SLAM Course by Cyrill Stachniss](https://www.youtube.com/watch?v=U6vr3iNrwRA&list=PLgnQpQtFTOGQrZ4O5QzbIHgl3b1JHimN_) | SLAM-Course (2013/14) |
| [SLAM - 5 Minutes with Cyrill](https://www.youtube.com/watch?v=BuRCJ2fegcc) | Short SLAM Tutorials |

</details>

<details>
<summary><strong>Datasets</strong></summary>

| Link | Description |
|------|-------------|
| [CroCoDL](https://zuriich.github.io/CroCoDL/) | AR localization benchmark from legged robots |
| [M2DGR](https://github.com/SJTU-ViSYS/M2DGR) | A Multi-modal and Multi-scenario SLAM Dataset for Ground Robots |
| [Fusionportable](https://fusionportable.github.io/dataset/fusionportable/) | A Multi-Sensor Campus-Scene Dataset for Evaluation of Localization and Mapping Accuracy on Diverse Platforms |
| [FusionPortable V2](https://fusionportable.github.io/dataset/fusionportable_v2/) | From Campus to Highway: A Unified Multi-Sensor Dataset for Generalized SLAM Across Diverse Platforms and Scalable Environments |
| [MCD](https://mcdviral.github.io/) | Diverse Large-Scale Multi-Campus Dataset for Robot Perception |
| [BotanicGarden](https://github.com/robot-pesg/BotanicGarden) | A high-quality dataset for robot navigation in unstructured natural environments |
| [Oxford Spires](https://dynamic.robots.ox.ac.uk/datasets/oxford-spires/) | Captured around well-known landmarks in Oxford using a custom-built multi-sensor perception unit as well as a millimetre-accurate map from a terrestrial LiDAR scanner. |

</details>

<details>
<summary><strong>Structure-from-Motion (SfM)</strong></summary>

| Link | Description |
|------|-------------|
| [GLOMAP](https://github.com/colmap/glomap) | Global Structure-from-Motion Revisited |
| [COLMAP](https://github.com/colmap/colmap) | General-purpose SfM and MVS pipeline |

</details>

<details>
<summary><strong>Talks</strong></summary>

| Link | Description |
|------|-------------|
| [Daniel Cremers - Deep and Direct SLAM](https://www.youtube.com/watch?v=s9yc9-d-Vc8) | Tartan SLAM Series |
| [Andrew Davison - From SLAM to Spatial AI](https://www.youtube.com/watch?v=PQFfJnmK26A) | Robotics Today |
| [Graph-based Spatial AI](https://www.youtube.com/watch?v=svzQgfkrxZc) | Andrew Davison, Tartan SLAM Series |

</details>

<details>
<summary><strong>Other Tools</strong></summary>

| Link | Description |
|------|-------------|
| [Pixi](https://pixi.sh/latest/) | Developer package management tool |
| [Spectacular AI](https://spectacularai.github.io/docs/sdk/core.html) | SDK for real-time 3D mapping and 6-DoF tracking |

</details>

<details>
<summary><strong>More Resources</strong></summary>

| Link | Description |
|------|-------------|
| [Awesome SLAM Datasets](https://github.com/youngguncho/awesome-slam-datasets) | A curated list of SLAM datasets |

</details>


