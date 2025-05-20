# AVDM: Controllable Adversarial Diffusion Model for Vessel-to-Volume Synthesis

This repository is dedicated to the implementation of **AVDM**, a novel framework introduced in our paper titled *"AVDM: Controllable Adversarial Diffusion Model for Vessel-to-Volume Synthesis"*, submitted to miccai 2025.

AVDM integrates adversarial supervision into a diffusion model to synthesize high-fidelity 3D volumes with controllable structural variations, addressing challenges in medical image analysis such as domain gaps and data scarcity.

## Project Overview
- **Key Features**:
  - Controllable synthesis via a segmenter-based discriminator.
  - Superior generative fidelity and cross-domain generalizability.
  - High-resolution output aligned with vessel annotations.
- **Applications**: Medical imaging, vascular disease diagnosis, synthetic data generation.

## Code Availability
- **Status**: The code will be made publicly available upon acceptance of the paper. the code will be released here once accepted.

## Repository Structure (Post-Release)
Once available, the repository will include:
- **`src/`**: Core AVDM model implementation.
- **`data/`**: Instructions for accessing/preprocessing datasets (e.g., ADAM, CoW, IXI-HH).

## Datasets
Experiments leverage publicly available 3D blood vessel datasets:
Details on dataset preparation will be provided upon code release.

## Installation (Post-Release)
After code publication:
1. Clone the repository:
   ```bash
   git clone https://github.com/[yourusername]/AVDM.git
   cd AVDM
   pip install -r requirements.txt
   
