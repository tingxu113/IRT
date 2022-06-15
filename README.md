# An Iterative Regularization Method based on Tensor Subspace Representation for Hyperspectral Image Super-Resolution 

**Homepage:** https://liangjiandeng.github.io/ and https://tingxu113.github.io/

# How to use?
- Directly run: ``Demo.m`` 

 
# Citation
```bibtex
@ARTICLE{xu2022tgrs,
author={T. Xu, T.-Z. Huang, L.-J. Deng, and N. Yokoya},
booktitle={IEEE Trans. Geosci. Remote Sens.},
title={An Iterative Regularization Method based on Tensor Subspace Representation for Hyperspectral Image Super-Resolution},
year={2022},
pages={},
}
```


# Method

***Motivation:*** Statistical analysis of low tensor tubal rank on seven HR-HSIs (the same color represents the same dataset). (a)–(f) Normalized tensor singular value curve of original HR-HSI and five permuted HR-HSIs, respectively.
<img src="fig-to-show/2.png" width = "90%" />

(a) Diagram of TenSR and MatSR. (b) HSI-SR results by using TenSR and MatSR with different subspace dimensions. 
<img src="fig-to-show/3.png" width = "50%" />

 The spatial–spectral nonlocal self-similarity property of the tensor coefficient.
<img src="fig-to-show/4.png" width = "60%" />




***Overall Framework:*** The framework of our model. The details of our framework can be found in Sect. III.

<img src="fig-to-show/1.png" width = "90%" />





***Final Model:*** 

<img src="fig-to-show/5.png" width = "50%" />



***Iterative Regularization Algorithm:*** 

<img src="fig-to-show/6.png" width = "50%" />

***Visual Results:*** HSI-SR results of Indian Pines. The first and second rows present the results consisting of 11th, 48th, and 128th band of the fused images under
SNR = 15 dB and the corresponding error maps, respectively. The blue block shows the representation region.

<img src="fig-to-show/7.png" width = "90%" />


***Quantitative Results:*** Quantitative evaluation of different methods on Indian Pines dataset with four noise cases

<img src="fig-to-show/8.png" width = "50%" />
