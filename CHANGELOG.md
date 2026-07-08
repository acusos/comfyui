# Changelog

All notable changes to this ComfyUI configuration repository are recorded here.

---

## 2026-07-08

### Repository

- Created Git repository.
- Added project structure.
- Added repository documentation.
- Added ComfyUI configuration.
- Added verified HunyuanVideo workflow.

### Installation

- Installed latest ComfyUI.
- Configured external model paths using `extra_model_paths.yaml`.
- Models stored under `/models/comfyui`.

### HunyuanVideo 1.5

Successfully verified:

- Native ComfyUI workflow
- Official Comfy-Org model pack
- 720p Text-to-Video
- Qwen 2.5 VL text encoder
- ByT5 text encoder
- HunyuanVideo 1.5 VAE

### Hardware

Host:
- ai (192.168.20.116)

Operating System:
- Ubuntu 24.04 LTS

CPU:
- AMD Ryzen 9 9950X3D

GPU:
- NVIDIA GeForce RTX 5090 32GB

Driver:
- 595.71.05

CUDA:
- 13.2

### Validation

First successful render completed.

Observed during generation:

- GPU Utilization: 100%
- GPU Power: 552 W
- GPU Memory: 26.8 GB
- Temperature: 76°C

Baseline established for future optimisation.

