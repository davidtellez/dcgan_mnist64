### DCGAN MNIST 64x64

Implementation of a DCGAN system to generate realistic MNIST digits at 64x64 resolution in Tensorflow. After 40 epochs of training, you should get these results:

images of real and fake mnist
images training tensorboard

### Usage

1. Launch ```jupyter notebook``` and browse to ```http://localhost:8888/```
2. Open [DCGAN MNIST tutorial.ipynb](DCGAN MNIST tutorial.ipynb)
3. Run all to start training
4. Use Tensorboard to monitor the training: ```tensorboard --logdir YOUR_DIR``` and browse to ```http://localhost:6006/```

### Requisites

- [Anaconda Python 3.5](https://www.continuum.io/downloads)
- [Tensorflow 0.12.0-rc1](https://www.tensorflow.org/)
- GPU for fast training (although CPU-only is supported)

### References

- [Generative Adversarial Networks](http://arxiv.org/abs/1406.2661)
- [Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks](http://arxiv.org/abs/1511.06434)
- [Image Completion with Deep Learning in TensorFlow](http://bamos.github.io/2016/08/09/deep-completion/)



