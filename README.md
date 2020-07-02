# FPS-Victory-BayesianNetwork
<p align="center">
   <img src="figures/model_graph.png" width="300">
</p>

This project describes a simple Bayesian Network model for assessing players' victory in a 1v1 FPS game match, inspired by ![Microsoft's TrueSkill](https://www.microsoft.com/en-us/research/project/trueskill-ranking-system/).

# Requirements
Our code only requires pgmpy as a dependency:
```
pip install pgmpy
```

Note: pgmpy requires PyTorch, which can mess your CUDA installation, so we recommend running it as a Colab notebook.

# Code
The code is available as a jupyter notebook in ![FPS_Victory_model.ipynb](
FPS_Victory_model.ipynb) file.
