# NIR Tutorial at NICE_2024

## Tutorial on the Neuromorphic Intermediate Representation

This is the landing page for the tutorial on the [Neuromorphic Intermediate Representation (NIR)](https://github.com/neuromorphs/NIR) on 26/4/2024 in San Diego at the [NICE conference 2024](https://niceworkshop.org/nice-2024/).

### Abstract

The Neuromorphic Intermediate Representation (NIR) is a universal format for defining and exchanging neuromorphic models. Since its creation during the 2023 Telluride Neuromorphic workshop, NIR has matured and is available as open-source software (https://github.com/neuromorphs/NIR). NIR currently supports 7 SNN software frameworks and 4 neuromorphic hardware platforms. In this tutorial we will present the concepts behind NIR and show its versatility in live demonstrations. The hands-on projects target both users of neuromorphic technology to learn to convert SNN models from one framework to another, and developers that want to extend NIR or interface it with their own tools.

The hands-on examples will be provided as Jupyter Notebooks which can be run on Google Colab. Please bring your own laptop.

### Tutorial Overview

- Introduction to NIR, its motivation and its design (presentation)
- **NIR for Users:** Train SNN in snnTorch and deploy it in Norse using NIR ([Notebook](notebooks/nir_demo/snntorch_to_norse.ipynb))
- Q&A / break
- **Live demo:** Deployment of SCNN on SpiNNaker2 ([Notebook](notebooks/spinnaker2_demo/spinnaker2_demo.ipynb))
- **NIR behind the scenes:** Synfire Chain with NIR and Brian2 ([Notebook](notebooks/nir_to_brian2/nir_to_brian2.ipynb))
- Direction for Future, Q&A, Feedback and discussion

### Tutors

- Bernhard Vogginger (TU Dresden)
- Jason Eshraghian (University of California, Santa Cruz)

## More about NIR

- Code: https://github.com/neuromorphs/NIR
- Documentation: https://nnir.readthedocs.io
- Paper: https://arxiv.org/abs/2311.14641

**You have questions about NIR or need support? Please join us on [Discord](https://discord.gg/JRMRGP9h3c).**

![Image NIR platforms](figures/nir_frameworks.png)
