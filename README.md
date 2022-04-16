# KCRL
This is the public repository of the code implementation for KCRL. 
## Requirements
The code is tested with the following configuration:

`Python=3.6.10`, `numpy=1.18.1`, `pandas=1.0.1`, `scikit-learn=0.22.1`, `scipy=1.4.1`, `tensorflow=1.13.1`, `networkx`, `pyyaml=5.3`, `pytz=2019.3`, `matplotlib=3.1.3`
## Instructions
Run KCRL with any dataset:

`python kcrl_demo.py`

***Detailed instructions***:

1. Set the initial parameters in the `python kcrl_demo.py` file. 
2. To use prior knowledge, provide the existing edges (0 or 1) in the prior knowledge matrix in `python kcrl_demo.py` file. 
Detailed comments available in the file. 

## Acknowledgement
Our code has been benefited from the following existing works. We are really thankful to the corresponding authors.

DAGs With NOTEARS https://github.com/xunzheng/notears

Causal Discovery With Reinforcement Learning https://github.com/huawei-noah/trustworthyAI.git

gCastle package https://github.com/huawei-noah/trustworthyAI/tree/master/gcastle

Neural Combinatorial Optimization with RL https://github.com/MichelDeudon/neural-combinatorial-optimization-rl-tensorflow
