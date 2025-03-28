https://github.com/user-attachments/assets/1233ae1e-a9e8-4787-b77b-609ad5c37aaf

# Fault-Tolerant Model Predictive Control for Spacecraft

In this package we provide the source for the article "Fault-Tolerant Model Predictive Control for Spacecraft" R. Stockner, P. Roque, M. Charitidou, and Dimos V. Dimarogonas.

## Running the demo
This package relies on [Python Poetry](https://python-poetry.org/docs/#installing-with-the-official-installer) (tested with version 2.1.1) and **Python 3.10 or 3.12**. After making sure that Python Poetry is correctly installed, following commands:

1. Clone the repository:
```bash
git clone git@github.com:DISCOWER/fault-tolerant-mpc.git
```

_Optional_: Configure `poetry` to create a local virtual environment. This is recommended to use the project with IDEs such as VSCode.
```bash
poetry config virtualenvs.in-project true
```

2. Install the `ft_mpc` library:
```bash
cd fault-tolerant-mpc
poetry install
```

3. Run the demo script:
```bash
poetry run python examples/sim.py
```

## ROS 2 Demonstration

A ROS 2 demonstration using KTH's [ATMOS](https://atmos.discower.io) platform will be provided soon!

## Citing this work
To cite this work, please use the following BibTeX entry:
```bibtex
@article{stockner2022fault,
  title={Fault-Tolerant Model Predictive Control for Spacecraft},
  author={Stockner, R. and Roque, P. and Charitidou, M. and Dimarogonas, Dimos V.},
  year={2022}
}
```