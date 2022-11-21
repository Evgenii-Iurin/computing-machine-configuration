# Konfiguracja maszyny obliczeniowej

### **System**

| OS | Kernel |
| --- | --- |
| Linux | 5.4.0-125-generic |

```bash
$ uname
>> Linux
$ uname -r
>> 5.4.0-125-generic
```

### Zainstalowane biblioteki

|  | Version |
| --- | --- |
| Python | 3.8.10 |
| CUDA | 11.8 |
| Torch | 1.13.0+cu117 |
| TensorFlow | 2.10.0 |
| TensorRT | 8.5.0-1+cuda11.8 |
| Tensorflow_gpu | 2.11.0 |
| Keras | 2.11.0 |
| Keras-Application | 1.0.8 |
| Keras-Preprocessing | 1.1.1 |
| Numpy | 1.18.5 |
| Scipy | 0.19.1 |
| Onnx | 1.4.1 |
| Pillow | 8.1.2 |
| Pucuda | 2020.1 |
| PyYAML | 5.4.1 |
| RPi.GPIO | 0.7.0 |
| Tensorboard-plugin-wit | 1.7.0 |
| Tensorboard | 2.4.1 |
| Tensorflow-estimator | 2.11.0 |
| Torchvision | 0.14.0 |
| Torchaudio | 0.13.0 |
| Nvidia-cudnn-cu11 | 8.5.0.96 |
| Nvidia-cuda-nvrtc-cu11 | 11.7.99 |
| Nvidia-cublas-cu11 | 11.10.3.66 |
| Nvidia-cuda-runtime-cu11 | 11.7.99 |
| Protobuf | 3.19.6 |
| Tensorflow_io_gcs_filesystem | 0.27.0 |

### Jak sprawdzić aktualną wersję biblioteki.

**CUDA**

```bash
$ nvcc --version
```

**PyTorch**

```bash
$ python3
>>>import torch
>>>print(torch.__version__)
```

**TensorFlow**

```bash
$ python3
>>> import tensorflow as tf
>>> print(tf.__version__)
```

**TensorRT**

```bash
$ dpkg -l | grep nvinfer
```
