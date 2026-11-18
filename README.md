# Vittorio Prodomo

AI engineer working on computer vision, document AI and MLOps, with a Ph.D. in privacy-preserving machine learning. Based in Naples, Italy.

For two years I was the sole AI engineer of an industrial computer-vision programme for the inspection of concrete bridges from drone and robot imagery. In 2026 I also designed a document-AI pipeline that reads a scanned archive of almost 8,000 historical test certificates with vision-language models.

## Toolkits

| Repository | What it does |
|---|---|
| [tt-toolkit](https://github.com/vittorio-prodomo/tt-toolkit) | Config-driven training, evaluation and deployment of instance-segmentation models (RF-DETR-Seg, Mask2Former, YOLO-seg): on-the-fly tiling, exact multi-GPU mAP, ONNX/TensorRT export |
| [dt-toolkit](https://github.com/vittorio-prodomo/dt-toolkit) | Command-line building blocks for detection and segmentation datasets: convert, tile, filter, merge, split; FiftyOne and CVAT bridges |
| [se-toolkit](https://github.com/vittorio-prodomo/se-toolkit) | Sweeps of sliced-inference hyperparameters scored against ground truth |
| [cocoyolo](https://github.com/vittorio-prodomo/cocoyolo) | COCO ↔ YOLO dataset label format converter |

## Upstream contributions and security

- Credited with [CVE-2026-53656](https://github.com/advisories/GHSA-q78p-hj9h-5466) in FiftyOne: cross-origin reads of local data through a wildcard CORS policy
- [cvat-ai/cvat#10306](https://github.com/cvat-ai/cvat/pull/10306): closed the public exposure of the Nuclio dashboard in CVAT's serverless deployment
- [roboflow/rf-detr#812](https://github.com/roboflow/rf-detr/pull/812): ONNX export fix
- [voxel51/fiftyone#7056](https://github.com/voxel51/fiftyone/pull/7056): CVAT mask import fix

The ML forks on this account (RF-DETR, SAHI, FiftyOne, CVAT and others) carry the patches those toolkits depend on.

## Research

- [Towards the integration of Privacy-Preserving technologies in future mobile networking](https://doi.org/10.1016/j.comcom.2026.108445), Computer Communications, 2026
- [Privacy-Preserving Data Obfuscation for Credit Scoring](https://doi.org/10.1145/3672608.3707864), ACM/SIGAPP Symposium on Applied Computing (SAC), 2025
- Automated Multiclass Damage Detection in RC Bridges Using Drone Imagery and Deep Learning Models, Conference on Artificial Intelligence in Structural Engineering (ARISTE), 2025
- [SCIPER: Secure Collaborative Inference via Privacy-Enhancing Regularization](https://doi.org/10.1109/TP.2024.3513254), IEEE Transactions on Privacy, 2024
- [Trading Accuracy for Privacy in Machine Learning Tasks: An Empirical Analysis](https://doi.org/10.1109/CNS53000.2021.9729036), IEEE Conference on Communications and Network Security (CNS), 2021 (poster paper)
- U.S. Patent 12,651,167 B2, "Privacy Preservation in Neural Networks", 2026

Two more papers are under review.

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/vittorio-prodomo)

Most of the other repositories here are modules and forks for my tabletop-gaming setup (Foundry VTT).
