# Generative Adversarial Networks (GAN)

[![Launch Codespace](https://img.shields.io/badge/launch-codespace-24292E?logo=github)](https://github.com/codespaces/new/adamelliotfields/gan)

GANs were a breakthrough in generative modeling when they were introduced back in 2014. A GAN consists of two neural networks, a generator and a discriminator, trained simultaneously. The generator learns to create data that is indistinguishable from real data, while the discriminator learns to distinguish between real and fake data. The two networks are trained in a "game" where the generator tries to fool the discriminator and the discriminator tries to not be fooled. Eventually an equilibrium is reached where the generator produces realistic data that the discriminator cannot distinguish from real data. At this point, the generator can be deployed to create new data. The best example of this is [This Person Does Not Exist](https://thispersondoesnotexist.com).

These are notebooks with implementations of different GAN architectures on different datasets. All models are written in Keras 3 and you can view the runs on [W&B](https://wandb.ai/adamelliotfields).

## Notebooks

<!-- [**GAN: Generative Adversarial Networks**](https://arxiv.org/abs/1406.2661) (Goodfellow et al. 2014) -->
<!-- [**cGAN: Conditional Generative Adversarial Nets**](https://arxiv.org/abs/1411.1784) (Mirza & Osindero 2014) -->
* [**DCGAN: Deep Convolutional Generative Adversarial Nets**](https://arxiv.org/abs/1511.06434) (Radford et al. 2015)
  - [MNIST](./dcgan/mnist.ipynb)
<!-- [**InfoGAN**](./infogan/notebook.ipynb): [Interpretable Representation Learning by Information Maximizing Generative Adversarial Nets](https://arxiv.org/abs/1606.03657) (Chen et al. 2016) -->
<!-- [**ACGAN**](./acgan/notebook.ipynb): [Auxiliary Classifier GAN](https://arxiv.org/abs/1610.09585) (Odena et al. 2016) -->
<!-- [**CycleGAN**](./cyclegan/notebook.ipynb): [Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks](https://arxiv.org/abs/1703.10593) (Zhu et al. 2017) -->
<!-- [**WGAN**](./wgan/notebook.ipynb): [Wasserstein GAN](https://arxiv.org/abs/1701.07875) (Arjovsky et al. 2017) -->
<!-- [**WGAN-GP**](./wgan-gp/notebook.ipynb): [Improved Training of Wasserstein GANs](https://arxiv.org/abs/1704.00028) (Gulrajani et al. 2017) -->
<!-- [**SAGAN**](./sagan/notebook.ipynb): [Self-Attention Generative Adversarial Networks](https://arxiv.org/abs/1805.08318) (Zhang et al. 2018) -->
<!-- [**StyleGAN**](./stylegan/notebook.ipynb): [A Style-Based Generator Architecture for Generative Adversarial Networks](https://arxiv.org/abs/1812.04948) (Karras et al. 2018) -->
<!-- [**StyleGAN2**](./stylegan2/notebook.ipynb): [Analyzing and Improving the Image Quality of StyleGAN](https://arxiv.org/abs/1912.04958) (Karras et al. 2019) -->

## Resources

* <https://www.freecodecamp.org/news/an-intuitive-introduction-to-generative-adversarial-networks-gans-7a2264a81394>
* <https://danieltakeshi.github.io/2017/03/05/understanding-generative-adversarial-networks>
* <https://neptune.ai/blog/gan-loss-functions>
* [NIPS Tutorial: GANs](https://arxiv.org/abs/1701.00160) (Ian Goodfellow 2016)
