# ComfyUI Installation

## Server

- Hostname: ai
- IP: 192.168.20.116
- OS: Ubuntu 24.04 LTS

## Hardware

- CPU: AMD Ryzen 9 9950X3D
- GPU: NVIDIA GeForce RTX 5090 32GB
- RAM: 96GB DDR5
- CUDA: 13.2
- NVIDIA Driver: 595.71.05

## Directories

Application:
/var/lib/docker/ComfyUI

Models:
/models/comfyui

Configuration Repository:
/data/projects/comfyui

## Verified Models

Diffusion:
- hunyuanvideo1.5_720p_t2v_fp16.safetensors

Text Encoders:
- qwen_2.5_vl_7b_fp8_scaled.safetensors
- byt5_small_glyphxl_fp16.safetensors

VAE:
- hunyuanvideo15_vae_fp16.safetensors

## Status

Verified working:

- Native ComfyUI
- HunyuanVideo 1.5
- RTX 5090
- 720p Text-to-Video
- Official Comfy-Org workflow

