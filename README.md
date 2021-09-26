# Auto-SCMA (Sparse Code Multiple Access) Python-Pytorch Implementation

[![Conference](http://img.shields.io/badge/NCC-2021-4b44ce.svg)](https://www.iitk.ac.in/ncc2021/) [![Paper](http://img.shields.io/badge/Paper-B31B1B.svg)](https://ieeexplore.ieee.org/document/9530173?fbclid=IwAR0-bSnIyp5nzRX4MS5fD_GCmRDDyXHZ9o_oiI8sgZQ0ACXeEmKyhpSL2Ck)

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
