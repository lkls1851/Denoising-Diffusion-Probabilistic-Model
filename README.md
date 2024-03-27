# Denoising-Diffusion-Probabilistic-Model

1. ‘ddpm_weights.pth’ : Contains the trained weights of the DDPM model.
2. ‘Generated’ : Contains grayscale images of generated images.
3. ‘Actual’ : Contains randomly sampled images from actual dataset.
4. ‘DDPM.ipynb’ : Notebook for implementing actual code
For calculating FID values for camparing the distribution in generated and actual images,
Run the following commands in the directory: </br>
pip3 install pytorch-fid </br>
python3 -m pytorch_fid Generated Actual --device cuda:0 </br>

The trained weights in the form of PyTorch weights uploaded: https://drive.google.com/file/d/1PuTiw5279Zh54HLYtJO8qVOfEvARdh5J/view?usp=sharing

