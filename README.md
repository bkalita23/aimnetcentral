[![Release](https://img.shields.io/github/v/release/isayevlab/aimnetcentral)](https://img.shields.io/github/v/release/isayevlab/aimnetcentral)
[![Build status](https://img.shields.io/github/actions/workflow/status/isayevlab/aimnetcentral/main.yml?branch=main)](https://github.com/isayevlab/aimnetcentral/actions/workflows/main.yml?query=branch%3Amain)
[![codecov](https://codecov.io/gh/isayevlab/aimnetcentral/branch/main/graph/badge.svg)](https://codecov.io/gh/isayevlab/aimnetcentral)
[![Commit activity](https://img.shields.io/github/commit-activity/m/isayevlab/aimnetcentral)](https://img.shields.io/github/commit-activity/m/isayevlab/aimnetcentral)
[![License](https://img.shields.io/github/license/isayevlab/aimnetcentral)](https://img.shields.io/github/license/isayevlab/aimnetcentral)

- **Github repository**: <https://github.com/isayevlab/aimnetcentral/>
- **Documentation** <https://isayevlab.github.io/aimnetcentral/>

# AIMNet2 : ML interatomic potential for fast and accurate atomistic simulations

## Key Features

- Accurate and Versatile: AIMNet2 excels at modeling neutral, charged, organic, and elemental-organic systems.
- Flexible Interfaces: Use AIMNet2 through convenient calculators for popular simulation packages like ASE and PySisyphus.
- Flexible Long-Range Interactions: Optionally employ the Dumped-Shifted Force (DSF) or Ewald summation Coulomb models for accurate calculations in large or periodic systems.

## Installation

1. Install [PyTorch](https://pytorch.org/) version for your CUDA archirecture

- CUDA 12.6

  `pip install torch --index-url https://download.pytorch.org/whl/cu126`

- CUDA 11.8

  `pip install torch --index-url https://download.pytorch.org/whl/cu118`

- CPU only

  `pip install torch`

2. Install AIMNet2 code

   `pip install git+https://github.com/isayevlab/aimnetcentral.git`

## Installation with conda
1. Create a conda environment python 3.12
 `conda create -n aimnetcentral python=3.12`
 `conda activate aimnetcentral`
2. install pytorch 2.7.0
 `conda install conda-forge::pytorch` 
3. Install other dependencies as required
4. Install AIMNet2
 `pip install git+https://github.com/isayevlab/aimnetcentral.git`
 or
 `git clone https://github.com/isayevlab/aimnetcentral.git`
 `cd aimnetcentral`
 `pip install -e .`