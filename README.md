# Biologically Informed Graph Attention Network for Interpretable Brain Connectivity Analysis

[![Paper](https://img.shields.io/badge/IJCNN-2026-00629B.svg)](https://ieeexplore.ieee.org/abstract/document/11729314)
[![DOI](https://img.shields.io/badge/DOI-10.1109%2FIJCNN69854.2026.11729314-blue.svg)](https://doi.org/10.1109/IJCNN69854.2026.11729314)

Official implementation of **"Biologically Informed Graph Attention Network for Interpretable Brain Connectivity Analysis"**, published at the *2026 International Joint Conference on Neural Networks (IJCNN)*.

**Authors:** Roger Zhu, Rishi Upadhyay

## Overview

We introduce a heterogeneous graph framework for diffusion MRI that captures the structural features of white matter tracts. White matter clusters and anatomical regions are represented as nodes, and edges link them where they spatially intersect. GraphSAGE aggregates node features, and multi-head Graph Attention Network (GAT) layers provide interpretability.

On the Human Connectome Project (HCP) S1200 dataset, the model reaches an **AUC of 0.891** for sex classification. That matches existing models while using much less training data. Attention scores identify the white matter tracts and anatomical regions that drive the predictions.

## Data

This work uses diffusion MRI data from the [Human Connectome Project (HCP) S1200 release](https://www.humanconnectome.org/study/hcp-young-adult). Access requires accepting the HCP data use terms. Data is not distributed with this repository.

## Citation

If you find this work useful, please cite:

```bibtex
@inproceedings{zhu2026biologically,
  author    = {Zhu, Roger and Upadhyay, Rishi},
  title     = {Biologically Informed Graph Attention Network for Interpretable Brain Connectivity Analysis},
  booktitle = {2026 International Joint Conference on Neural Networks (IJCNN)},
  year      = {2026},
  pages     = {1--6},
  doi       = {10.1109/IJCNN69854.2026.11729314}
}
```

## Acknowledgments

Data were provided by the Human Connectome Project, WU-Minn Consortium (Principal Investigators: David Van Essen and Kamil Ugurbil; 1U54MH091657), funded by the 16 NIH Institutes and Centers that support the NIH Blueprint for Neuroscience Research, and by the McDonnell Center for Systems Neuroscience at Washington University.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
