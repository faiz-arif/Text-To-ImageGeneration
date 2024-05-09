# Text to Image Generation Using DCGAN

This implementation is a PyTorch-based version of [Generative Adversarial Text-to-Image Synthesis paper]. The architecture of this model draws inspiration from DCGAN (Deep Convolutional Generative Adversarial Network).

## Requirements

- h5py==3.6.0
- numpy==1.21.5
- Pillow==10.0.0
- torch==2.0.0

## Dataset

We used [Caltech-UCSD Birds 200](http://www.vision.caltech.edu/visipedia/CUB-200.html) and text embeddings provided by [Reed Scott et al.](https://github.com/reedscot/icml2016)

## Repository

```
├── models
├     └──  dcgan_model.py
├── utils.py
├── data_util.py
├── requirements.txt
└──  DCGAN_Text2Image.ipynb
```



