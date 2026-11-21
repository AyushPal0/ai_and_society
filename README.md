# AI and Society · CSET485 Assignment 1

This assignment audits two predictive models on ProPublica’s COMPAS recidivism dataset for roll **0352**. The analysis uses a stratified 70/30 split with seed **352**.

- [PDF report](output/pdf/CSET485_Assignment_1_0352.pdf)
- [Executed Jupyter notebook](CSET485_COMPAS_0352.ipynb)

## Reproduce the analysis

Use Python 3.13 in an isolated environment. From the repository root, install the pinned dependencies and start JupyterLab:

```console
python -m pip install -r requirements.txt
python -m pip install jupyterlab
python -m jupyterlab
```

Open `CSET485_COMPAS_0352.ipynb`, select the Python 3 kernel from that environment, and run all cells. The notebook downloads the assigned CSV from a pinned [ProPublica source commit](https://github.com/propublica/compas-analysis/blob/c062fbb5fa84f6c99d82f432c46b405f3a0ca5ec/compas-scores-two-years.csv) and checks its SHA-256 hash. To run offline, place the byte-identical CSV in the notebook directory as `.compas-source.csv`. The formulas, analysis choices, output tables, and figures are documented in the notebook.
