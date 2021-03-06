## Dependency
* Python3.6(numpy, scipy, pickle, h5py),
* PyTorch0.2,
* Cuda8.0, Cudnn5.1 (If GPU is used)

## Effects
This is the DCGAN implemented by PyTorch. The training dataset is CelebA ["http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html"], after training for 25 epochs, the generator can generate human portraits that look like real humans. Some examples generated by GAN are presented below:

<p align="middle">
  <img src="https://github.com/liangstein/DCGAN-PyTorch/blob/master/generated_examples.png" width="400"/>
</p>


After training for 113 epochs, the generated images looks a bit better:
<p align="middle">
  <img src="https://github.com/liangstein/DCGAN-PyTorch/blob/master/generated_examples2.png" width="400"/>
</p>
