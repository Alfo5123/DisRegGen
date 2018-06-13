# DisRegGen

This is a pytorch implementation of the paper [Discriminative Regularization for Generative Models](https://arxiv.org/pdf/1602.03220.pdf) by Alex Lamb, Vincent Dumoulin and Aaron Courville.


## Reference Papers
- [Discriminative Regularization for Generative Models](https://arxiv.org/pdf/1602.03220.pdf)
- [Auto-Encoding Variational Bayes](https://arxiv.org/pdf/1312.6114.pdf)
- [Unsupervised  representation  learning  with  deep  convolutional  generative  adversarial  networks](https://arxiv.org/pdf/1511.06434.pdf)
- [Very deep convolutional  networks  for  large-scale  image  recognition](https://arxiv.org/pdf/1409.1556.pdf)
- [Perceptual Losses for Real-Time Style Transfer and Super-Resolution](https://cs.stanford.edu/people/jcjohns/papers/eccv16/JohnsonECCV16.pdf)
- [Deconvolution and Checkerboard Artifacts](https://distill.pub/2016/deconv-checkerboard/)


## Results

Original                  |  VAE                   | DisRegGen             |
:-------------------------:|:-------------------------: |:-------------------------:
![](results/sample_original_cifar.png)  |  ![](results/sample_vae_cifar_99.png) | ![](results/sample_vae_disreg_cifar_300.png)
![](results/sample_original_svhn.png)  |  ![](results/sample_vae_svhn_99.png) | ![](results/sample_svhn_100_bs32.png)


## Reference Repository
For further reference you can check the [author's implementation](https://github.com/vdumoulin/discgen).

## License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/Alfo5123/DisRecGen/blob/master/LICENSE) file for details.
