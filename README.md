<h2 align="center">
Auto-SCMA (Sparse Code Multiple Access) Python-Pytorch Implementation
</h1>

<p align="center">
  <a href="https://www.iitk.ac.in/ncc2021/"><img src="http://img.shields.io/badge/NCC-2021-4b44ce.svg"></a>
  <a href="https://ieeexplore.ieee.org/document/9530173?fbclid=IwAR0-bSnIyp5nzRX4MS5fD_GCmRDDyXHZ9o_oiI8sgZQ0ACXeEmKyhpSL2Ck"><img src="http://img.shields.io/badge/Paper-IEEE_Explore-B31B1B.svg"></a>
  <a href="https://github.com/ekagra-ranjan/ekagra-ranjan.github.io/blob/main/assets/resume/publications/slides/Auto-SCMA-ppt.pptx?raw=true"><img src="http://img.shields.io/badge/Slides-PDF-orange.svg"></a>
</p>

Source code for [NCC 2021](https://www.iitk.ac.in/ncc2021/) paper: [**Auto-SCMA: Learning Codebook for Sparse Code Multiple Access using Machine Learning**](https://ieeexplore.ieee.org/document/9530173?fbclid=IwAR0-bSnIyp5nzRX4MS5fD_GCmRDDyXHZ9o_oiI8sgZQ0ACXeEmKyhpSL2Ck)

## Abstract
*Sparse Code Multiple Access (SCMA) is an effective non-orthogonal multiple access technique that facilitates communication among users with limited orthogonal resources. Currently, its performance is limited by the quality of the hand-crafted codebook. We propose Auto-SCMA, a machine learning based approach that learns the codebook using gradient descent while using a Message Passing Algorithm decoder. It is the first machine learning based approach to generalize successfully on
the Rayleigh fading channel. It is able to learn an effective codebook without involving any human effort in the process.
Our experimental results show that Auto-SCMA outperforms previous methods including machine learning based methods.*


![image](https://user-images.githubusercontent.com/3116519/118371488-74a62980-b5ca-11eb-84ea-e56c823f744e.png)
<p align="center">
<img src="https://user-images.githubusercontent.com/3116519/118371853-0febce80-b5cc-11eb-8d50-c5b2086eb649.png" width="700" >
</p>

<br>

## Comparison with Deep Learning Aided SCMA (D-SCMA)

|     Method      | [D-SCMA](https://ieeexplore.ieee.org/document/8254356) | Auto-SCMA |
| :----------------: | :--------------------------------------: | :--------------------------------------: |
|    Number of parameters     |                  > 1 million                   |                  96                   |
| Rayleigh Fading Generalization | No | Yes |
| Outperforms ML decoder on hand-crafted codeboook | No | Yes |
| Zero Human effort | No | Yes |

<br>

## Results

<p align="center">
<img src="https://user-images.githubusercontent.com/3116519/118371896-4b869880-b5cc-11eb-9942-3cf666191f03.png" width="500">
</p>

## How to Use
The repo contains Jupyter notebooks that can be viewed and run online via Google Colab using the colab button that appears in Github.

## File Description
* `SCMA_Python.ipynb` - Colab notebook for SCMA written in Python. It uses Pytorch to leverage GPU for faster runtime. `is_fading` and `is_noise` can be used to toggle Rayleigh fading noise and AWGN noise respectively. The notebook contains two popular handcrafted SCMA codebooks.
* `AWGN_Fast_DiffSCMA_Shared.ipynb` - Colab notebook for Auto-SCMA on AWGN channel
* `Fading_Fast_DiffSCMA_Shared.ipynb` - Colab notebook for Auto-SCMA on Rayleigh fading channel  
