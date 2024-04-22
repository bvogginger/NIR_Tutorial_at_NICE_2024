## Create conda environment

1. Create conda environment from `.yml` file
```
conda env create -f env_nce24.yml
```

2. Activate your environment
```
conda activate env_nce24
```

3. Install snnTorch from specific commit

```
pip install git+https://github.com/jeshraghian/snntorch@94fc028960f3222c23ff88ea59cc05907a576d3a
```

4. Install py-spinnaker2
```
git clone https://gitlab.com/spinnaker2/py-spinnaker2.git
pip install -e ./py-spinnaker2
```
