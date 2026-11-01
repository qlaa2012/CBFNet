# CBFNet

**CBFNet: Decoupling Global Semantics and Edge Differences via Complementary Branch Fusion for Medical Lesion Segmentation**

This repository is intended to provide the official implementation of CBFNet, a complementary branch fusion network for 2D medical lesion segmentation.

## Overview

CBFNet is designed to combine global contextual understanding with local boundary refinement through two complementary decoding pathways built on a shared Res2Net encoder:

- **Global Guidance Branch (GGB):** aggregates multilevel contextual features using receptive field blocks and hierarchical fusion.
- **Edge Difference Branch (EDB):** recalibrates multilevel features with frequency-aware attention and models structural differences through recursive feature subtraction.
- **Feature Fusion Module (FFM):** adaptively integrates the two branch predictions using spatially varying weights and residual refinement.

The method is evaluated on dermoscopic and colonoscopic lesion segmentation tasks, including within-dataset and cross-dataset settings.

## Repository Status

The accompanying manuscript is currently under review. To preserve the review and publication process, the complete source code and trained model weights are not publicly released at this stage.

Following acceptance of the manuscript, we intend to release the implementation and the materials required to reproduce the reported experiments in this repository. The planned release will include, where applicable:

- model architecture and module implementations;
- training and inference scripts;
- evaluation and metric-calculation code;
- experiment configurations and split information; and
- pretrained checkpoints, subject to dataset and distribution restrictions.

If you require the implementation or additional information before the public release, please contact the first author using the contact information provided in the manuscript.

## Datasets

The experiments use publicly available datasets for dermoscopic and colonoscopic lesion segmentation. The datasets are not redistributed in this repository. Users should obtain them from their original sources and comply with the corresponding licenses and terms of use.

## Citation

A citation entry will be added after the manuscript has been accepted and the final publication information is available.

## License

The license for the source code and released materials will be specified when the public implementation is released.
