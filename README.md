## Awesome resources on States Space Model.
This is a collection of resources related with states space model.
![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

## Contents

- [Papers](#papers)
  - [Prior works](#RelatedWorks)
  - [State Space Models](#SSM)
  - [Application](#application)
     - [Audio Waveform Generation](#Audio)
     - [Multi-dimensional Signals for Computer Vision](#CV)
     - [Time Series](#TS)
- [Code](#Code)
<a name="surveypapers" />

## Related Works
1. **Improving the Gating Mechanism of Recurrent Neural Networks.** *Albert Gu, Çaglar Gülçehre, T. Paine, Matthew W. Hoffman, Razvan Pascanu.* 2019 [paper] (https://arxiv.org/pdf/1910.09890.pdf)
2. **Legendre Memory Units: Continuous-Time Representation in Recurrent Neural Networks.** *Aaron R. Voelker, Ivana Kajić, C. Eliasmith.* 2019 [paper] (https://www.semanticscholar.org/paper/Legendre-Memory-Units%3A-Continuous-Time-in-Recurrent-Voelker-Kaji%C4%87/34eccf3528e4350543c76752cac978e0f2c5b7a2)
3. **Rethinking Attention with Performers.** *K. Choromanski, Valerii Likhosherstov, David Dohan, Xingyou Song, Andreea Gane, Tamás Sarlós, Peter Hawkins, Jared Davis, Afroz Mohiuddin, Lukasz Kaiser, David Belanger, Lucy J. Colwell, Adrian Weller.* 2020 [paper] (https://arxiv.org/pdf/2009.14794.pdf)
4. **HiPPO: Recurrent Memory with Optimal Polynomial Projections.** *Albert Gu, Tri Dao, Stefano Ermon, A. Rudra, C. Ré.* 2020 [paper] (https://arxiv.org/pdf/2008.07669.pdf)
5. **FMMformer: Efficient and Flexible Transformer via Decomposed Near-field and Far-field Attention.** *T. Nguyen, Vai Suliafu, S. Osher, Long Chen, Bao Wang.* 2021 [Paper] (https://arxiv.org/pdf/2108.02347.pdf)
6. **Nyströmformer: A Nyström-Based Algorithm for Approximating Self-Attention.** *Yunyang Xiong, Zhanpeng Zeng, Rudrasis Chakraborty, Mingxing Tan, G. Fung, Yin Li, Vikas Singh.* [paper] (https://arxiv.org/pdf/2102.03902.pdf)
7. **Random Feature Attention.** *Hao Peng, Nikolaos Pappas, Dani Yogatama, Roy Schwartz, Noah A. Smith, Lingpeng Kong.* 2021 [paper] (https://arxiv.org/pdf/2103.02143.pdf)
8. **FlexConv: Continuous Kernel Convolutions with Differentiable Kernel Sizes.** *David W. Romero, Robert-Jan Bruintjes, Jakub M. Tomczak, E. Bekkers, M. Hoogendoorn, J. V. Gemert.* 2021 [paper] (https://arxiv.org/pdf/2110.08059.pdf)
9. **Block-Recurrent Transformers.** *DeLesley S. Hutchins, Imanol Schlag, Yuhuai Wu, Ethan Dyer, Behnam Neyshabur.* 2022 [paper] (https://arxiv.org/pdf/2203.07852.pdf)
10. **CKConv: Continuous Kernel Convolution For Sequential Data.** *David W. Romero, Anna Kuzina, E. Bekkers, Jakub M. Tomczak, M. Hoogendoorn.* 2022 [paper] (https://arxiv.org/pdf/2102.02611.pdf)
11. **Mega: Moving Average Equipped Gated Attention.** *Xuezhe Ma, Chunting Zhou, Xiang Kong, Junxian He, Liangke Gui, Graham Neubig, Jonathan May, Luke Zettlemoyer.* [paper] (https://arxiv.org/pdf/2209.10655.pdf)
12. ****Sparse Modular Activation for Efficient Sequence Modeling.** *Liliang Ren, Yang Liu, Shuo Wang, Yichong Xu, Chenguang Zhu, Chengxiang Zhai.* 2023 [paper] (https://arxiv.org/pdf/2306.11197.pdf)
13. **Hyena Hierarchy: Towards Larger Convolutional Language Models.** *Michael Poli, Stefano Massaroli, Eric Q. Nguyen, Daniel Y. Fu, Tri Dao, S. Baccus, Y. Bengio, Stefano Ermon, Christopher Ré.* 2023 [paper] (https://arxiv.org/pdf/2302.10866.pdf)
14. **Sequence Modeling with Multiresolution Convolutional Memory.** *Jiaxin Shi, Ke Alexander Wang, E. Fox.* 2023 [paper] (https://arxiv.org/pdf/2305.01638.pdf)
15. **Resurrecting Recurrent Neural Networks for Long Sequences.** *Antonio Orvieto, Samuel L. Smith, Albert Gu, Anushan Fernando, Caglar Gulcehre, Razvan Pascanu, Soham De.* 2023 [paper] (https://arxiv.org/pdf/2303.06349.pdf)


<a name="State Space Models" />

## State Space Models
1. **HiPPO: Recurrent Memory with Optimal Polynomial Projections.** *Albert Gu, Tri Dao, Stefano Ermon, A. Rudra, C. Ré.* 2020 [paper] (https://arxiv.org/pdf/2008.07669.pdf)
2. **Combining Recurrent, Convolutional, and Continuous-time Models with Linear State-Space Layers.** *Albert Gu, Isys Johnson, Karan Goel, Khaled Kamal Saab, Tri Dao, A. Rudra, Christopher R'e.* 2021 [paper] (https://arxiv.org/pdf/2110.13985.pdf)
3. **Efficiently Modeling Long Sequences with Structured State Spaces.** *Albert Gu, Karan Goel, Christopher R'e.* 2021 [paper] (https://arxiv.org/pdf/2111.00396.pdf)
4. **Efficient Long Sequence Modeling via State Space Augmented Transformer.** *Simiao Zuo, Xiaodong Liu, Jian Jiao, Denis Xavier Charles, Eren Manavoglu, Tuo Zhao, Jianfeng Gao.* [paper] (https://arxiv.org/pdf/2212.08136.pdf)
5. **Simplifying and Understanding State Space Models with Diagonal Linear RNNs.** *Ankit Gupta, Harsh Mehta, Jonathan Berant.* 2022 [paper] (https://arxiv.org/pdf/2212.00768.pdf)
6. **What Makes Convolutional Models Great on Long Sequence Modeling?** *Yuhong Li, Tianle Cai, Yi Zhang, De-huai Chen, Debadeepta Dey.* [paper] (https://arxiv.org/pdf/2210.09298.pdf)
7. **How to Train Your HiPPO: State Space Models with Generalized Orthogonal Basis Projections.** *Albert Gu, Isys Johnson, Aman Timalsina, A. Rudra, Christopher Ré.* [paper] (https://arxiv.org/pdf/2206.12037.pdf)
8. **Long Range Language Modeling via Gated State Spaces.** *Harsh Mehta, Ankit Gupta, Ashok Cutkosky, Behnam Neyshabur.* [paper] (https://arxiv.org/pdf/2206.13947.pdf)
9. **Hungry Hungry Hippos: Towards Language Modeling with State Space Models.** *Tri Dao, Daniel Y. Fu, Khaled Kamal Saab, A. Thomas, A. Rudra, Christopher Ré.* [paper] (https://arxiv.org/pdf/2212.14052.pdf)
10. **Liquid Structural State-Space Models。** *Ramin M. Hasani, Mathias Lechner, Tsun-Hsuan Wang, Makram Chahine, Alexander Amini, Daniela Rus.* [paper] (https://arxiv.org/pdf/2209.12951.pdf)
11. **Diagonal State Spaces are as Effective as Structured State Spaces.** *Ankit Gupta, Jonathan Berant.* 2022 [paper] (https://arxiv.org/pdf/2203.14343.pdf)
12. **On the Parameterization and Initialization of Diagonal State Space Models.** *Albert Gu, Ankit Gupta, Karan Goel, Christopher Ré.* 2022 [paper] (https://arxiv.org/pdf/2206.11893.pdf)
13. **Simplified State Space Layers for Sequence Modeling.** *Jimmy Smith, Andrew Warrington, Scott W. Linderman.* 2022 [paper] (https://arxiv.org/pdf/2208.04933.pdf)
14. **A Quantitative Review on Language Model Efficiency Research.** *Meng Jiang, Hy Dang, Lingbo Tong.* 2023 [paper] (https://arxiv.org/pdf/2306.01768.pdf)
15. **Block-State Transformers.** *Mahan Fathi, Jonathan Pilault, Pierre-Luc Bacon, C. Pal, Orhan Firat, Ross Goroshin.* 2023 [paper] (https://arxiv.org/pdf/2306.09539.pdf)
16. **Robustifying State-space Models for Long Sequences via Approximate Diagonalization.** *Annan Yu, Arnur Nigmetov, Dmitriy Morozov, Michael W. Mahoney, N. Benjamin Erichson.* 2023 [paper] (https://arxiv.org/pdf/2310.01698.pdf)
17. **Simple Hardware-Efficient Long Convolutions for Sequence Modeling.** *Daniel Y. Fu, Elliot L. Epstein, E. Nguyen, A. Thomas, Michael Zhang, Tri Dao, A. Rudra, Christopher Ré.* 2023 [paper] (https://arxiv.org/pdf/2302.06646.pdf)
18. **Mamba: Linear-Time Sequence Modeling with Selective State Spaces.** *Albert Gu, Tri Dao.* 2023 [paper] (https://arxiv.org/ftp/arxiv/papers/2312/2312.00752.pdf)

    

## Application
<a name="Audio" />
### Audio Waveform Generation
1. **It's Raw! Audio Generation with State-Space Models.** *Karan Goel, Albert Gu, Chris Donahue, Christopher R'e.* 2022 [paper] (https://arxiv.org/pdf/2202.09729.pdf)


<a name="CV" />
### Multi-dimensional Signals for Computer Vision
1. **S4ND: Modeling Images and Videos as Multidimensional Signals with State Spaces.** *Eric Nguyen, Karan Goel, Albert Gu, Gordon Downs, Preey Shah, Tri Dao, Stephen Baccus, Christopher Ré.* 2023 [paper] (https://openreview.net/pdf?id=5WuQNQwy56M)


<a name='TS' />
### Time Series Modeling
1. **Effectively Modeling Time Series with Simple Discrete State Spaces.** *Michael Zhang, Khaled Kamal Saab, Michael Poli, Tri Dao, Karan Goel, Christopher Ré.* 2023 [paper] (https://arxiv.org/pdf/2303.09489.pdf)


## Code
1. [S4](https://github.com/state-spaces/s4?tab=readme-ov-file)
1. [S5](https://github.com/lindermanlab/S5)
1. [Mamba](https://github.com/state-spaces/mamba)
