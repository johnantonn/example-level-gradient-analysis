# Example-level gradient analysis

Experiments with **per-example gradients** on a small 2D `Perceptron`: how gradient information at the training-example level reflects each point’s contribution to learning.

> **Status:** Personal / university coursework archive — **not actively maintained**. Dependencies and tooling may be outdated.

## How to run

Use **Python 3** and **Jupyter** (`pip install jupyter` plus NumPy/Matplotlib as needed). Open `example-level-gradient-analysis.ipynb` and run cells top to bottom.

### Summary
The notebook walks through a simple `Perceptron` on synthetic 2D datasets and inspects gradient norms (and related quantities) **per training example**, to relate local gradient signal to how much each example shapes the update.

### How to
Open `example-level-gradient-analysis.ipynb` and run the cells top to bottom.
