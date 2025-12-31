This project implements a Denoising Diffusion Probabilistic Model (DDPM) on the MNIST dataset using a time-conditioned UNet, and evaluates sample quality with FID.

## 1. Environment Setup (Conda)
conda create -n cvpdl-hw3 python=3.10 -y
conda activate cvpdl-hw3
conda install pytorch torchvision cudatoolkit=12.1 -c pytorch -c nvidia
pip install -r requirements.txt

python -m ipykernel install --user --name cvpdl-hw3
jupyter notebook
