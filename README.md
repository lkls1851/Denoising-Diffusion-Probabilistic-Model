# Denoising-Diffusion-Probabilistic-Model

1. ‘ddpm_weights.pth’ : Contains the trained weights of the DDPM model.
2. ‘Generated’ : Contains grayscale images of generated images.
3. ‘Actual’ : Contains randomly sampled images from actual dataset.
4. ‘DDPM.ipynb’ : Notebook for implementing actual code
For calculating FID values for camparing the distribution in generated and actual images,
Run the following commands in the directory:
// pip3 install pytorch-fid
// python3 -m pytorch_fid Generated Actual --device cuda:0
