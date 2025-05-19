# Image Restoration based on Weak-to-Strong Diffusion-Transformer Model(WSDiT)
Luan Ma, and Lei Liu*

 
## Requirements
- CUDA 10.1 (or later)
- Python 3.9 (or later)
- Pytorch 1.8.1 (or later)
- Torchvision 0.19
- OpenCV 4.7.0
- tensorboard, skimage, scipy, lmdb, tqdm, yaml, einops, natsort

## Training and Evaluation

Training and testing instructions for Image Deraining, Image Deblurring, and Real Image Denoising are provied in the links below. 

<table>
  <tr>
    <th align="center">Task</th>
    <th align="center">Training</th>
    <th align="center">Testing</th>
  </tr>
  <tr>
    <td align="center">Image Deraining</td>
    <td align="center"><a href="Deraining/README.md#training">Link</a></td>
    <td align="center"><a href="Deraining/README.md#testing">Link</a></td>
  </tr>
  <tr>
    <td align="center">Image Deblurring</td>
    <td align="center"><a href="Deblurring/README.md#training">Link</a></td>
    <td align="center"><a href="Deblurring/README.md#testing">Link</a></td>
  </tr>
  <tr>
     <td align="center">Real Image Denoising</td>
    <td align="center"><a href="Denoising/README.md#training">Link</a></td>
    <td align="center"><a href="Denoising/README.md#testing">Link</a></td>
  </tr>
</table>

## Acknowledgments 
This code is based on the [BasicSR](https://github.com/xinntao/BasicSR) toolbox and [Restormer](https://github.com/swz30/Restormer), [WeatherDiffusion](https://github.com/IGITUGraz/WeatherDiffusion). 

