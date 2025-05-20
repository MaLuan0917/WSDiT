# Image Restoration based on Weak-to-Strong Diffusion-Transformer Model(WSDiT)
Luan Ma and Lei Liu*

## Weak Stage Architecture of the Weak-to-Strong Diffusion-Transformer Model (WDiT)

<img src = "https://github.com/MaLuan0917/WSDiT/raw/main/Figs/Weak.jpg#pic_center">  

## Strong Stage Architecture of the Weak-to-Strong Diffusion-Transformer Model (SDiT)

<img src = "https://github.com/MaLuan0917/WSDiT/raw/main/Figs/strong.jpg#pic_center"> 

 
## Requirements
- CUDA 10.1 (or later)
- Python 3.9 (or later)
- Pytorch 1.8.1 (or later)
- Torchvision 0.19
- OpenCV 4.7.0
- tensorboard, skimage, scipy, lmdb, tqdm, yaml, einops, natsort

## Training and Evaluation

Training and testing instructions and visualization results for Image Deraining, Image Deblurring, and Real Image Denoising are provied in the links below. 

<table>
  <tr>
    <th align="center">Task</th>
    <th align="center">Training</th>
    <th align="center">Testing</th>
    <th align="center">WSDiT's Visual Results</th>
  </tr>
  <tr>
    <td align="center">Image Deraining</td>
    <td align="center"><a href="Deraining/README.md#training">Link</a></td>
    <td align="center"><a href="Deraining/README.md#testing">Link</a></td>
    <td align="center"><a href="https://pan.baidu.com/s/1uQorXLaH3so42_EZUW-FZA 提取码: 0917">Download</a></td>
  </tr>
  <tr>
    <td align="center">Image Deblurring</td>
    <td align="center"><a href="Deblurring/README.md#training">Link</a></td>
    <td align="center"><a href="Deblurring/README.md#testing">Link</a></td>
    <td align="center"><a href="https://pan.baidu.com/s/1EroXXSh1mAp0dBA_8aV2Ag 提取码: 0917 ">Download</a></td>
  </tr>
  <tr>
     <td align="center">Real Image Denoising</td>
    <td align="center"><a href="Denoising/README.md#training">Link</a></td>
    <td align="center"><a href="Denoising/README.md#testing">Link</a></td>
    <td align="center"><a href="https://pan.baidu.com/s/1TN2L7ijgAsf9I7SwM2Y9UA 提取码: 0917">Download</a></td>
  </tr>
</table>

## Experimental Results

<details>
<summary><strong>Image Deraining</strong> (click to expand) </summary>

<p align="center"><img src = "https://github.com/MaLuan0917/WSDiT/raw/main/Figs/deraining.jpg#pic_center"></p> 
<p align="center"><img src = "https://github.com/MaLuan0917/WSDiT/raw/main/Figs/table1.jpg#pic_center" width="1000"></p> 

</details>

<details>
<summary><strong>Image Deblurring</strong> (click to expand) </summary>

<p align="center"><img src = "https://github.com/MaLuan0917/WSDiT/raw/main/Figs/deblurring.jpg#pic_center" width="500"></p>
<p align="center"><img src = "https://github.com/MaLuan0917/WSDiT/raw/main/Figs/table3.jpg#pic_center" width="1000"></p>
</details>

<details>
<summary><strong>Real Image Denoising</strong> (click to expand) </summary>

<p align="center"><img src = "https://github.com/MaLuan0917/WSDiT/raw/main/Figs/SIDD.jpg" width="500"></p>
<p align="center"><img src = "https://github.com/MaLuan0917/WSDiT/raw/main/Figs/DND.jpg" width="500"></p>
<p align="center"><img src = "https://github.com/MaLuan0917/WSDiT/raw/main/Figs/table2.jpg#pic_center" width="1000"></p>
</details>


## Acknowledgments 
This code is based on the [BasicSR](https://github.com/xinntao/BasicSR) toolbox and [Restormer](https://github.com/swz30/Restormer), [WeatherDiffusion](https://github.com/IGITUGraz/WeatherDiffusion). 

