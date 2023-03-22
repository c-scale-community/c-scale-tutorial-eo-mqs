# EO-MQS Tutorial for C-SCALE

This project provides a brief introduction of the Earth Observation Metadata Query Service ([EO-MQS](mqs.eodc.eu/browser)) for C-SCALE.

## Getting started

`docker compose up -d`

This compose file launches one service:
1. JupyterLab with packages listed in [environment.jupyter.yml](environment.jupyter.yml) installed.

Access the JupyterLab Web UI like so:

```bash
http://127.0.0.1:8888/lab?token=eo-mqs
```

Data required to be accessible from Jupyter is located in the directory `data` and sample notebooks are provided in the folder `notebooks`.

There are very basic sample notebooks available to get a feeling of how to interact with the MQS using Python.

General recommendation: make use of the [STAC Index](https://stacindex.org/ecosystem) to find the tool in the STAC Ecosystem that suits your needs best.

## Slides 

The slides of the presentation from 22nd March 2023 are available as PDF in this repository [eo-mqs-demo-20230322.pdf](eo-mqs-demo-20230322.pdf).

## YouTube 

The recording of the session is available on YouTube.

## Useful links

Links shown in the demo and other useful resources is provided in the data folder: [useful-links.json](data/useful-links.json).


