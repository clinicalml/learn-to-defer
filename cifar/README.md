## CIFAR experiments

We include 4 notebooks to be able recreate our learning to defer experiments on the CIFAR-10/100 datasets, each notebook records the metrics measured for a single expert k, to be able to recreate Figure 3, one needs to run the cifar10_* notebooks for every expert k. To be able to reproduce our results on CIFAR-10H in Table 2, follow the notebook [cifar10h_defer.ipynb](cifar10h_defer.ipynb).

To summarize, we include the following notebooks

*  [cifar10_defer_ours.ipynb](cifar\cifar10_defer_ours.ipynb) reproduces the results for our method L_{CE}^{\alpha} for a single expert k.

* [cifar10_defer_baselines.ipynb](cifar\cifar10_defer_baselines.ipynb) reproduces the results for the Confidence and LearnedOracle baseline for a single expert k.

* [cifar10_defer_madras.ipynb](cifar\cifar10_defer_madras.ipynb) reproduces the results for the MixOfExp (Madras et al. 2018) baseline for a single expert k.

* [cifar10h_defer.ipynb](cifar\cifar10h_defer.ipynb) reproduces the results recorded in Table 2 for CIFAR-10H.
