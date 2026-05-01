# SSL Pitch Estimation

This repository provides a tutorial on a **simplified implementation of PESTO, a self-supervised model for pitch estimation** [1]. It is mainly intended as a teaching material.

The main tutorial can be accessed in the notebook `ssl-pitch-estimation-tutorial.ipynb`.

## Run in Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MTG/ssl-pitch-estimation/blob/main/ssl-pitch-estimation-tutorial.ipynb)

Simply click the button above and be sure to run the install dependencies code cell provided.


## Run Locally

Clone the repository and install the dependencies listed in `pyproject.toml`

We recommend using [uv](https://docs.astral.sh/uv/) to create a virtual environment and to install dependencies.

```bash
uv venv
source .venv/bin/activate
uv sync
```

### References

We encourage you to check out the [original implementation](https://github.com/SonyCSLParis/pesto-full) from which this notebook is based and the paper [1].

Note that there is also a pip-installable minimal code implementation for inference only in this [fast implementation](https://github.com/SonyCSLParis/pesto) repository.

[1] A. Riou, “PESTO: Real‑Time Pitch Estimation with Self‑Supervised Transposition‑Equivariant Objective”, <i>Transactions of the International Society for Music Information Retrieval</i>, vol. 8, no. 1, p. 334–352, 2025, doi: [10.5334/tismir.251](https://doi.org/10.5334/TISMIR.251).
