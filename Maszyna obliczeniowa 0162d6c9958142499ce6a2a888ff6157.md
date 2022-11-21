# Maszyna obliczeniowa

**System**

OS: Linux

| OS | Kernel |
| --- | --- |
| Linux | 5.4.0-125-generic |

```bash
$ uname
>> Linux
$ uname -r
>> 5.4.0-125-generic
```

**CUDA**

Version: 11.8

**PyTorch**

Version: 1.13.0+cu117

```bash
$ python3
>>>import torch
>>>print(torch.__version__)
Version1.13.0+cu117
```

**TensorFlow**

Version: 2.10.0

```bash
$ python3
>>> import tensorflow as tf
>>> print(tf.__version__)
```

Przy instalacji tensorflow-gpu

![Untitled](Maszyna%20obliczeniowa%200162d6c9958142499ce6a2a888ff6157/Untitled.png)

**TensorRT**

```bash
$ dpkg -l | grep nvinfer
ii  libnvinfer-bin                    8.5.0-1+cuda11.8                  amd64        TensorRT binaries
ii  libnvinfer-dev                    8.5.0-1+cuda11.8                  amd64        TensorRT development libraries and headers
ii  libnvinfer-plugin-dev             8.5.0-1+cuda11.8                  amd64        TensorRT plugin libraries and headers
ii  libnvinfer-plugin8                8.5.0-1+cuda11.8                  amd64        TensorRT plugin library
ii  libnvinfer8                       8.5.0-1+cuda11.8                  amd64        TensorRT runtime libraries
```