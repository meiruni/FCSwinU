
# FSwinU：




## Network Architecture

- The overall architecture diagram of our proposed multiscale spatial–spectral Transformer network.
  <!-- ![Illustration of MSST-Net](figure/framework.png) -->

<div aligh=center witdh="200"><img src="figure/framework.png"></div>


- The architecture diagram of the masked patches autoencoder.
  <!-- ![Illustration of hsi pretrain](figure/pretrain_hsi.png) -->
  <img src="figure/pretrain_hsi.png" aligh=center witdh="50px">


- The architecture diagram of the masked bands autoencoder.
  <!-- ![Illustration of msi pretrain](figure/pretrain_msi.png) -->
  <img src="figure/pretrain_msi.png" aligh=center witdh="50px">



## 1. Create Envirement:

- Python 3 (Recommend to use [Anaconda](https://www.anaconda.com/download/#linux))

- NVIDIA GPU + [CUDA](https://developer.nvidia.com/cuda-downloads)

pip install timm
pip install thop
pip install scikit-image
pip install scipy
pip install einops
pip install opencv-python
## 2. Data Preparation:

- Download the CAVE dataset from <a href="https://www1.cs.columbia.edu/CAVE/databases/multispectral">here</a>.


## Citation

If this repo helps you, please consider citing our works:

