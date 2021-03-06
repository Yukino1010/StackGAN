# StackGAN

## Introduce
This is an implementation of StackGAN++ [https://arxiv.org/abs/1710.10916]. <br>
StackGAN is a breakthrough in high-resolution image generation. To generate high-resolution images, StackGAN consists of multiple generators
and multiple discriminators to tackle with different resolutions respectively. In addition, the author add Color-consistency regularization on the generator, to make sure the consistency of color in different resolution.

## Network Structure

![image](https://github.com/Yukino1010/StackGAN/blob/master/stack.png)
(https://arxiv.org/abs/1710.10916)

## Hyperparameters
- D_DIM = 64
- G_DIM= 32
- START_EPOCH = 1
- START_ITER = 1
- EPOCHS = 50
- ITERS = 3000
- DECAY_EPOCH = 50
- BATCH_SIZE = 16
- Z_DIM = 100
- TARGET_IMG_SIZE = 256

## Data
This implementation using CelebA (a large-scale face attributes dataset ) <br>
https://mmlab.ie.cuhk.edu.hk/projects/CelebA.html

## Result

![image](image/epoch_50_fake_image.jpg)
![image](image/epoch_74_fake_image.jpg) <br>
![image](image/epoch_80_fake_image.jpg)
![image](image/epoch_46_fake_image.jpg)


## References
1. ***StackGAN*** [[arxiv](https://arxiv.org/abs/1710.10916)]
2. ***Tensorflow implementation of the StackGAN++*** (https://github.com/zacharynevin/StackGAN)
