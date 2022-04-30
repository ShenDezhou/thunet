# Models
1. **Neural networks**  
    * Layers / Layer-wise ops
        - Add
        - Flatten
        - Multiply
        - Softmax
        - Fully-connected/Dense
        - Sparse evolutionary connections
        - LSTM
        - Elman-style RNN
        - Max + average pooling
        - Dot-product attention
        - Embedding layer
        - Restricted Boltzmann machine (w. CD-n training)
        - 2D deconvolution (w. padding and stride)
        - 2D convolution (w. padding, dilation, and stride)
        - 1D convolution (w. padding, dilation, stride, and causality)
    * Modules
        - Bidirectional LSTM
        - ResNet-style residual blocks (identity and convolution)
        - WaveNet-style residual blocks with dilated causal convolutions
        - Transformer-style multi-headed scaled dot product attention
    * Regularizers
        - Dropout
    * Normalization
        - Batch normalization (spatial and temporal)
        - Layer normalization (spatial and temporal)
    * Optimizers
        - SGD w/ momentum
        - AdaGrad
        - RMSProp
        - Adam
    * Learning Rate Schedulers
        - Constant
        - Exponential
        - Noam/Transformer
        - Dlib scheduler
    * Weight Initializers
        - Glorot/Xavier uniform and normal
        - He/Kaiming uniform and normal
        - Standard and truncated normal
    * Losses
        - Cross entropy
        - Squared error
        - Bernoulli VAE loss
        - Wasserstein loss with gradient penalty
        - Noise contrastive estimation loss
    * Activations
        - ReLU
        - Tanh
        - Affine
        - Sigmoid
        - Leaky ReLU
        - ELU
        - SELU
        - Exponential
        - Hard Sigmoid
        - Softplus
    * Models
        - Bernoulli variational autoencoder
        - Wasserstein GAN with gradient penalty
        - word2vec encoder with skip-gram and CBOW architectures
    * Utilities
        - `col2im` (MATLAB port)
        - `im2col` (MATLAB port)
        - `conv1D`
        - `conv2D`
        - `deconv2D`
        - `minibatch`
2. **BERT** 
   * vanilla BERT
   * simple BERT