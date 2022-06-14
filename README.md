## InaTEWS Training Python - Obspy - PyGMT

## You can also open the notebooks in the Binder application online...

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/seismologie/InaTEWS-Training/main)

## Install libraries

### Using python env
```
python -m venv geo
source geo/bin/activate
pip install pygmt
pip install obspy
```

### Using conda env (recommended)
```
conda create --name geo --channel conda-forge pandas pygmt obspy jupyter notebook
```




```
conda env export > environment.yml
```
