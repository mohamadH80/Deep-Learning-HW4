## Q1 Notebook:
In this notebook, we aim to predict permeability of 2000 molecules. Each molecule is given to the RNN models using its SMILES code.
For baseline, we train a FC on one-hot encoded of SMILES strings. In the next two sections, we implement a LSTM and then
BiLSTM to get better accuracy in our binary prediction. 


## VAE_CVAE Notebook:
In this notebook, we implement a Variational Autoencoder using MLP to generate MNIST images. Also, we have implemented Conditional Variational Autoencoder
to improve images quality. The 2 dimensional latent space is showen in last section.


## Q3 Notebook(Persian Poem Generator):
A SeqToSeq model is implemeneted to generate poem in persian language. We fine tune GPT2 pre-trained model using a suitable loss function. Perplexity measure is used to understand exact quality of outputs.


## Q4 Notebook:
This is an implementation of a type of auto encoders named Vector Quantized Variational Autoencoder or breifly VQ-VAE. The novelity in these networks is discrete latent space instead of continuous one. 
![image](https://github.com/mohamadH80/Deep-Learning-HW4/assets/84089279/a7be2846-dc7f-494d-8dfb-031f7cf89bcf)

Reference article link: https://arxiv.org/pdf/1711.00937.pdf

Paper Abstract:
Learning useful representations without supervision remains a key challenge in
 machine learning. In this paper, we propose a simple yet powerful generative
 model that learns such discrete representations. Our model, the Vector Quantised
Variational AutoEncoder (VQ-VAE), differs from VAEs in two key ways: the
 encoder network outputs discrete, rather than continuous, codes; and the prior
 is learnt rather than static. In order to learn a discrete latent representation, we
 incorporate ideas from vector quantisation (VQ). Using the VQ method allows the
 model to circumvent issues of “posterior collapse”-— where the latents are ignored
 when they are paired with a powerful autoregressive decoder-— typically observed
 in the VAE framework. Pairing these representations with an autoregressive prior,
 the model can generate high quality images, videos, and speech as well as doing
 high quality speaker conversion and unsupervised learning of phonemes, providing
 further evidence of the utility of the learnt representations.
