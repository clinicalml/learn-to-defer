# Consistent Estimators for Learning to Defer to an Expert
This repository includes the code  and experiments  for our [ICML 2020 paper Consistent Estimators for Learning to Defer to an Expert
 ](https://arxiv.org/abs/2006.01862) by Hussein Mozannar and David Sontag.

This repository is currently being expanded.

## Learning to defer to an Expert
Learning algorithms are often used in conjunction with expert decision makers in practical
scenarios, however this fact is largely ignored when designing these algorithms. In this project
we explore how to learn predictors that can either predict or choose to defer the decision to a
downstream expert. Our approach is based on a novel
reduction to cost sensitive learning where we give a consistent surrogate loss for cost sensitive
learning that generalizes the cross entropy loss. The loss described in detail in the papers is referred to as L_{CE}^{\alpha}.



## Citation

```
@article{mozannar2020consistent,
  title={Consistent Estimators for Learning to Defer to an Expert},
  author={Mozannar, Hussein and Sontag, David},
  journal={arXiv preprint arXiv:2006.01862},
  year={2020}
}
```
