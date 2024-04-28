The matlab code is only for Windows platforms. Besides, create the directory `E:\SIGA2014\workspace\`.

The 1.15 version of Tensorflow is no longer supported on 30XX GeForce GPUs. Please install the special version of Tensorflow maintained by NVIDIA in the following steps.
```shell
conda create -n  nvtf python=3.8
conda activate nvtf
pip install nvidia-pyindex
pip install nvidia-tensorflow
pip install scipy==1.9.0
```
Unfortunately, this is helpful only on Linux platforms.