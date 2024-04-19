# NIR to SpiNNaker2 Demo

## Instructions for running the demo in Google Collab

<a href="https://colab.research.google.com/github/bvogginger/NIR_Tutorial_at_NICE_2024/blob/main/notebooks/spinnaker2_demo/spinnaker2_demo.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

**Note: this will use the brian2 backend of py-spinnaker2**

## Instructions for running the Demo locally with a SpiNNaker2 Chip via Jupyter Lab

1. Create conda environment
```
conda create --name s2_demo python=3.10
```

2. Activate your environment
```
conda activate s2_demo
```

3. Install dependencies

```
conda install -c conda-forge jupyterlab
conda install -c conda-forge ipywidgets
conda install -c conda-forge nb_conda_kernels
conda install pytorch torchvision torchaudio cpuonly -c pytorch
conda install -c conda-forge tonic
```

4. Install NIR from source
```
pip install git+https://github.com/neuromorphs/NIR.git
```

5. Install py-spinnaker2 with s2-sim2lab-app to this conda environment as described [here](https://gitlab.com/spinnaker2/py-spinnaker2#installation).

6. Start jupyter lab

```
jupyter lab
```
