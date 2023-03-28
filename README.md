[![Binder](https://replay.notebooks.egi.eu/badge_logo.svg)](https://replay.notebooks.egi.eu/v2/gh/c-scale-community/c-scale-tutorial-eo-mqs/HEAD?labpath=notebooks%2F1-EO-MQS_DataDiscovery.ipynb)

# EO-MQS Tutorial for C-SCALE

This project provides a brief introduction of the Earth Observation Metadata Query Service
([EO-MQS](https://wiki.c-scale.eu/C-SCALE/c-scale-services/eo-mqs)) for C-SCALE.

## Getting started with docker

`docker compose up -d`

This compose file launches one service:
1. JupyterLab with packages listed in [environment.jupyter.yml](environment.jupyter.yml) installed.

Access the JupyterLab Web UI like so:

```bash
http://127.0.0.1:8888/lab?token=eo-mqs
```

## Getting started with EGI Replay

You can also run the notebooks using
[EGI Replay](https://replay.notebooks.egi.eu/v2/gh/c-scale-community/c-scale-tutorial-eo-mqs/HEAD?labpath=notebooks%2F1-EO-MQS_DataDiscovery.ipynb).

Pre-requisites:
* Create an [EGI Account](https://docs.egi.eu/users/aai/check-in/signup/)
* Enroll the `vo.notebooks.egi.eu` Virtual Organisation following this link:
  [https://aai.egi.eu/registry/co_petitions/start/coef:111](https://aai.egi.eu/registry/co_petitions/start/coef:111)

## Data

Data required to be accessible from Jupyter is located in the directory `data` and sample notebooks are provided in the folder `notebooks`.

There are very basic sample notebooks available to get a feeling of how to interact with the MQS using Python.

General recommendation: make use of the [STAC Index](https://stacindex.org/ecosystem) to find the tool in the STAC Ecosystem that suits your needs best.

## Slides 

The slides of the presentation from 22nd March 2023 are available as PDF in this repository [eo-mqs-demo-20230322.pdf](eo-mqs-demo-20230322.pdf).

## YouTube 

The recording of the session is available on [YouTube](https://youtu.be/cebnrOgoX_I).

## Useful links

Links shown in the demo and other useful resources is provided in the data folder: [useful-links.json](data/useful-links.json).
