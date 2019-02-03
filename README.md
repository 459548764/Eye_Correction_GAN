# GazeCorretion: Self-Guided Eye Manipulation in the wild using Generative Adversarial Networks
The code of paper "GazeCorrection: Self-Guided Eye Manipulation in the wild using Generative Adversarial Networks". Paper will published coming soon.

--------------------------------------------

![](img/t_input2.jpg)
![](img/t_output2.jpg)

![](img/gif/gif1/age.gif)
![](img/gif/gif2/age.gif)
![](img/gif/gif3/age.gif)

# Introduction

Gaze correction has a wide range of applications in the real life. For example,
this techniques can be applied for eye attention rectification for formal
personal or group photograph. We do not found effective methods for this problem.
In this paper, we proposed a new eye rotation algorithm for fast
eye attention rectification using a end-to-end networks. Our method is based on the
idea of eye in-painting and leverage encode-decode networks to learn the mapping from
the input facial image with the eye mask to the facial image with correct eye attention.
We use adversarial loss to improve the visual quality of generated samples. Moreover,
we propose a self-guided method to preserve the identity information of the in-painted images.
A new dataset has been collected for training and will be introduced in details.

## Network Architecture

Coming soon

## 

## Dependencies
* [Python 2.7](https://www.python.org/download/releases/2.7/)
* [Tensorflow 1.4+](https://github.com/tensorflow/tensorflow)


## Usage

- Clone this repo:
```bash
git clone https://github.com/zhangqianhui/Eye_Rotation_GAN.git
```
- Download the Eye_Rotation dataset

Coming soon!!!

- Train the model using the default parameter
```bash
python main.py 
```


# The process of Experiments

![](img/output.jpg)

# More Results

![](img/gif/gif4/age.gif)
![](img/gif/gif5/age.gif)
![](img/gif/gif6/age.gif)
![](img/gif/gif7/age.gif)
![](img/gif/gif8/age.gif)
![](img/gif/gif9/age.gif)
![](img/gif/gif10/age.gif)
![](img/gif/gif11/age.gif)
![](img/gif/age.gif)
            
# Reference code

- [Sparsely_Grouped_GAN](https://github.com/zhangqianhui/Sparsely-Grouped-GAN)

- [DCGAN tensorflow](https://github.com/carpedm20/DCGAN-tensorflow)

- [Spectral Norm tensorflow](https://github.com/taki0112/Spectral_Normalization-Tensorflow)

- [Exemplar-GAN-Eye-Inpainting-Tensorflow](https://github.com/zhangqianhui/Exemplar-GAN-Eye-Inpainting-Tensorflow.git)

- [ELEGANT](https://github.com/Prinsphield/ELEGANT)
