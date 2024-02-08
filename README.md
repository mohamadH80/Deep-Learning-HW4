## Q1 Notebook:
In this notebook, we aim to predict permeability of 2000 molecules. Each molecule is given to the RNN models using its SMILES code.
For baseline, we train a FC on one-hot encoded of SMILES strings. In the next two sections, we implement a LSTM and then
BiLSTM to get better accuracy in our binary prediction. 


## VAE_CVAE Notebook:
In this notebook, we implement a Variational Auto Encoder using MLP to generate MNIST images. Also, we have implemented Conditional Variational Auto Encoder
to improve images quality. The 2 dimensional latent space is showen in last section.


## Q3 Notebook(Persian Poem Generator):
A SeqToSeq model is implemeneted to generate poem in persian language. We fine tune GPT2 pre-trained model using a suitable loss function. Perplexity measure is used to understand exact quality of outputs.


## Q4 Notebook:
![image](https://github.com/mohamadH80/Deep-Learning-HW4/assets/84089279/a7be2846-dc7f-494d-8dfb-031f7cf89bcf)
