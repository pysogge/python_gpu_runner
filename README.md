# CUDA / NVIDIA GPU Test Python Scripts

## Start (after Setup):
```
conda activate conda3venv

python3 gpu_runner.py

python3 gpu_kernel.py
```

## Setup:
```
conda create --name conda3venv

conda activate conda3venv

conda install cudatoolkit

conda install numba
```

## The actual scripts were taken from Stack Overflow:
https://stackoverflow.com/questions/61982672/cuda-gpu-processing-typeerror-compile-kernel-got-an-unexpected-keyword-argum
