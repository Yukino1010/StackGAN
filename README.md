# StackGAN

## Introduce
This is an implementation of StackGAN++ [https://arxiv.org/abs/1710.10916]. <br>
StackGAN is a breakthrough of high-resolution image generation. To generate high-resolution image, StackGAN consists of multiple generators
and multiple discriminators to tackle with different resolution respectively. In addition, the authir add Color-consistency regularization on the generator, to make sure the consistency of color in different resolution.

## Network Structure

![image](https://github.com/Yukino1010/Style_Transfer_Part1/blob/master/1_y1siCwwrhkrBSTaY7QL5Xw.png)


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


## References
