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
conda install -c conda-forge jupyterlab ipywidgets nb_conda_kernels
conda install pytorch torchvision torchaudio cpuonly -c pytorch
conda install -c conda-forge tonic
```

New:

```
conda install -c conda-forge jupyterlab ipywidgets nb_conda_kernels
pip install torch==2.2.1 torchvision==0.17.1 torchaudio==2.2.1 --index-url https://download.pytorch.org/whl/cpu
```


4. Install py-spinnaker2 with s2-sim2lab-app to this conda environment as described [here](https://gitlab.com/spinnaker2/py-spinnaker2#installation).

5. Install tonic

```
pip install tonic
```


6. Start jupyter lab

```
jupyter lab
```
