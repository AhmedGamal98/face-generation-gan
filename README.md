# Face Generation with a DCGAN

> A Deep Convolutional Generative Adversarial Network (DCGAN) that learns to generate new human faces, trained on the CelebA dataset.

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)

## Overview

- **Discriminator:** a convolutional network with leaky ReLU and batch normalization that tells real faces from generated ones.
- **Generator:** turns a random noise vector into a 28×28×3 face image using transposed convolutions.
- **Training:** the generator and discriminator losses are optimized with Adam. The model is first tested on MNIST digits, then trained on CelebA faces.
- Generated samples are shown during training to track progress.

## Files

| File | Description |
| --- | --- |
| `dlnd_face_generation.ipynb` | Model code, training loop and generated samples |
| `dlnd_face_generation.html` | Exported notebook with all outputs, for quick viewing |

## Notes

This was the face-generation project of the **Udacity Deep Learning Nanodegree**. The notebook uses Udacity's helper modules (`helper.py`, `problem_unittests.py`) and the CelebA / MNIST datasets, which are not included here. Open the `.html` file to see the results without running anything.

## Author

**Ahmed Gamal Saber**, Full-Stack Web Developer & AI Engineer
[LinkedIn](https://linkedin.com/in/ahmed-gamal-saber-382081169) · [GitHub](https://github.com/AhmedGamal98)
