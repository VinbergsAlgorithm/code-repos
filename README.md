# code-repos

Known realizations of the Vinberg algorithm are added here as submodules. 

## What is included?

- `sage/` is our original realization in **Sagemath** (by Bogachev and Perepechko), [taken from this tag](https://github.com/aperep/vinal/releases/tag/0.2.0) as a subtree. 

- `python/` is a rewrite in **sympy** (again by Bogachev and Perepechko), [taken from here](https://github.com/aperep/vinal). It includes [CoxIter](https://rgugliel.github.io/CoxIter/) by Rafael Guglielmetti as a submodule, which is [taken from here](https://github.com/rgugliel/CoxIter).

- `julia/` is a reworked version in **Julia**, by Rémi Bottinelli, [taken from here](https://github.com/bottine/VinbergsAlgorithmNF).

- `cpp/src_vinberg/` is a *c++* realization by Mathieu Dutour Sikirić with numerous optimizations. [Taken from here](https://github.com/MathieuDutSik/polyhedral_common). 



## Install

To clone, use

```
git clone https://github.com/VinbergsAlgorithm/code-repos.git --recursive
```

To update the submodules, enter
`git submodule update --remote`

