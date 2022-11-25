# Colab-Stable-Diffusion-2-Depth

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/backnotprop/Colab-Stable-Diffusion-2-Depth/blob/main/%5BColab_Gradio%5D_stable_diffusion_2_depth.ipynb)

A simple notebook that launches Stable Diffusion 2.0 Depth (depth-to-image) demonstration via Gradio UI


This stable-diffusion-2-depth model is resumed from stable-diffusion-2-base (512-base-ema.ckpt) and finetuned for 200k steps. Added an extra input channel to process the (relative) depth prediction produced by MiDaS (dpt_hybrid) which is used as an additional conditioning.


### Note
This notebook uses Gradio's `share` feature to serve the UI via a public URL, through a tunnel over HTTPs. To add security, this notebook forces you to set a `user/password` combo to access the UI
