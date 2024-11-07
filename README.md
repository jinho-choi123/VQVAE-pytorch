# Vector Quantized Variational AutoEncoder Implementation

## Description
Implementation of Vector Quantized Variational AutoEncoder(VQ-VAE) using pytorch.

Please refer to the following blog post for more information about VQ-VAE

https://docs.jinhochoi.xyz/paper-reviews/vector-quantized-vae-vq-vae

## Getting Started

### Prerequisite
**python 3.11.10**

Use pyenv to set python version to 3.11.10
```
$ python --version
Python 3.11.10
```

**uv-python**

We are going to use [uv-python](https://github.com/astral-sh/uv) to install package and manage virtualenv.

### Install requirements

Run the following command to install requirements:
```
// initialize venv
$ uv venv

// activating the venv
$ source .venv/bin/activate 

// install required packages
$ uv pip install -r requirements.txt
```

### Run VAE

Execute jupyter lab using following command
```
$ jupyter lab
// this will run jupyter server, and you can open jupyter-notebook for vqvae_tutorial.ipynb file
```

Open vqvae_tutorial.ipynb file in jupyter lab, and run all the cells.

