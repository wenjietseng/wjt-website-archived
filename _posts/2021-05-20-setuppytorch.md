---
layout: post
title:  Setup PyTorch
date: 2021-05-20 00:03:00
# description: 
---

Follow the setup steps on [the GitHub homepage of PyTorch](https://github.com/pytorch/pytorch#installation).

- Install [Anaconda](https://www.anaconda.com/products/individual#download-section)
- Install [cuda](https://developer.nvidia.com/cuda-downloads)
- Install [cudnn](https://developer.nvidia.com/cudnn)
- [tutorial](https://docs.nvidia.com/deeplearning/cudnn/install-guide/index.html): unzip the cudnn.....zip and put files into cuda's folder.

What I got: Anaconda3, cuda 11.3, cudnn 8.2

check cuda version: `nvcc`
check GPU: `nvidia-smi`

Install on Windows

```{shell}
conda install astunparse numpy ninja pyyaml mkl mkl-include setuptools cmake cffi typing_extensions future six requests dataclasses
conda install -c conda-forge libuv=1.39
```

Conda did not find  I eventually used pip because conda already includes pip. Also, I realized I don't have to build from source. Using binary installation is much easier.

```{shell}
pip3 install torch==1.8.1+cu111 torchvision==0.9.1+cu111 torchaudio===0.8.1 -f https://download.pytorch.org/whl/torch_stable.html
```

Then I created a new python project for testing installation and it worked. I change the python into anacoda python (shows at the buttom-left of VScode) by modifying python.pythonPath and Ctrl+Shift+P select interpreter. Another setting is switching powershell in Terminal into Cmd prompt of anaconda. Therefore I can use python and venv of anaconda to develop PyTorch.

It taked quite some time to organize the environment. Perhaps I should just use pip and my original python. However, everything seemed ready. Next steps:

- easy PyTorch examples: play with datasets (e.g., MNIST), learn from examples will be quick
- we will also need to setup RL env (seems easier?) and play with RL examples.
- think about the VR project with computational techniques. (reading paper and collect ideas)
