# Lagrangian and Hamiltonian Neural Networks With a Dissipative System

Code and notebooks for our paper "Lagrangian and Hamiltonian Neural Networks for Dissipative System", which is under review at ICLR 2027.

## Getting started

Use Python 3.12. From the repository root:

```bash
pip install -r requirements.txt
cd experiments/lnn/undamped/noiseless
jupyter notebook experiment.ipynb
```

Run the notebook cells in order. To try another experiment, start Jupyter from that experiment's directory.

## Experiments

- `experiments/lnn/`: undamped and damped LNNs, including damped models with and without time as an input.
- `experiments/hnn/`: undamped HNNs, damped HNNs using canonical momentum and time, and Energy NN comparisons.

Each experiment contains an `experiment.ipynb` notebook. For LNNs, undamped HNNs, and Energy NNs, use `REPRODUCE_PAPER = True` to load the reference data and saved models, or `False` to regenerate data and retrain. The two damped HNN notebooks retrain from fixed random seeds.

Plots are saved to `figures/paper/`. Generated data and trained models are saved under each experiment's `runs/` directory.

## Citation

Coming Soon
