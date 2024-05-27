# Apple_Silicon_Torch

## Intro:
This repo to utilize the GPUs in MacBooks with Apple Silicon M1~M3.

## process.ipynb

A simple notebook that performs multiplying two matrices by the cpu and the MacBook GPU and compares the time required.


## Creating the virtual environment:

```
python3 -m venv .venv
source .venv/bin/activate
pip install -U pip
```

## Installing PyTorch:
```
pip install torch torchvision torchaudio
```


## Installing TensorFlow:

```
pip install tensorflow tensorflow-macos tensorflow-metal
```


## Installing JAX:

```
pip install jax-metal ml_dtypes==0.2.0 jax==0.4.26 jaxlib==0.4.26
```


# Resources:
The following resources:
https://github.com/svpino/apple-silicon
