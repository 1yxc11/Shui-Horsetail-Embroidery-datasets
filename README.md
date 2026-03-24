# VP-SHE: A Vector-based Parametric Simulation Framework for Shui Horsetail Embroidery

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](#)

## 1. Dataset Description
Shui Horsetail Embroidery is a traditional handicraft of the Shui ethnic group. Its most distinctive feature is the use of horsetail hair as a core, wrapped with silk threads to create a "horsetail snail" (thread coil), which is then stitched onto fabric.

This dataset provides high-fidelity visual references and precise geometric annotations to support:
* **Procedural Modeling:** Extracting geometric parameters such as spiral pitch and curvature.
* **Stitch Synthesis:** Training generative models for embroidery texture generation.
* **Digital Preservation:** Providing high-resolution vector assets for cultural heritage archiving.

## 2. Data Acquisition
* **Equipment:** Captured on-site using **iPhone 16** (utilizing Macro mode for ultra-fine texture details).
* **Sources:** * **Field Research:** Authentic samples collected from Sandu Shui Autonomous County, Guizhou Province.
    * **Web Collection:** Curated high-quality samples from major social media and visual platforms.

## 3. Dataset Scale
| Data Type | Quantity | Format  | Description |
| :--- | :--- |:--------| :--- |
| **Real-world Images** | 1,000 | `.png`  | Covering diverse motifs (e.g., butterflies, dragons). |
| **Vector Annotations** | 5 | `.svg`  | Detailed manual path tracing of core structures. |

## 4. Annotation Specification
The vector data is annotated using **Inkscape**:
* **Methodology:** Paths are fitted using **Bézier Curves** to represent the center-line.
* **Attributes:** Annotations include coordinate data and derived parametric information.

## 5. Repository Structure
```bash
VP-SHE-Dataset/
├── images/             # 1,000 raw embroidery images
├── annotations/        # Manual vector path data
├── docs/               # Documentation
├── LICENSE             # Creative Commons Attribution 4.0
└── README.md
```

## 6. Citation

If you use this dataset or the VP-SHE framework in your research, please cite our working paper:

@article{vpshe2026,
  title={VP-SHE: A Vector-based Parametric Simulation Framework for Shui Horsetail Embroidery},
  author={YI},
  journal={},
  year={2026},
  url={https://github.com/YourUsername/VP-SHE-Dataset}
}