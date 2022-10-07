### 需要下载对应版本的pytorch

[官网](https://pytorch.org/get-started/locally/#no-cuda-1)
[教程](https://blog.csdn.net/qq_46126258/article/details/112708781)

### cuda版本
```
nvidia-smi
```

### 下载pytorch
```
pip install torch --pre --extra-index-url https://download.pytorch.org/whl/nightly/cu116

```
### 下载Torchvision
```
pip install torchvision --pre --extra-index-url https://download.pytorch.org/whl/nightly/cu116

```
### 下载Torchaudio
```
pip install torchaudio --pre --extra-index-url https://download.pytorch.org/whl/nightly/cu116

```
### 下载三件套
```
pip install torch torchvision torchaudio --pre --extra-index-url https://download.pytorch.org/whl/nightly/cu116

```