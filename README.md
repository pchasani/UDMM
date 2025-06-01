# UDMM - Unimodal Mixture Modeling of Univariate Multimodal Data

This repository contains the **Python implementation** of:

- `UU-test`: A statistical **unimodality** test for deciding data unimodality (for the **MATLAB version**, see [MATLAB UU-test Repository](https://github.com/pchasani/UUtest))
- `UniSplit`: A valley detection method for determining valley points of univariate multimodal datasets and obtaining partitions into unimodal subsets.
- `UDMM`: A statistical mixture model (**Unimodal Mixture Model**), where each mixture component corresponds to a unimodal distribution.


Unimodality constitutes a key property indicating grouping behavior of the
data around a single mode of its density. We propose a method that partitions
univariate data into unimodal subsets through recursive splitting around
valley points of the data density. For valley point detection, we introduce
properties of critical points on the convex hull of the empirical cumulative
density function (ecdf) plot that provide indications on the existence of density
valleys. Next, we apply a unimodal data modeling approach that provides
a statistical model for each obtained unimodal subset in the form of
a Uniform Mixture Model (UMM). Consequently, a hierarchical statistical
model of the initial dataset is obtained in the form of a mixture of UMMs,
named as the Unimodal Mixture Model (UDMM). The proposed method
is non-parametric, hyperparameter-free, automatically estimates the number
of unimodal subsets and provides accurate statistical models as indicated by
experimental results on clustering and density estimation tasks.

## Reference

```bibtex
@misc{chasani2024statisticalmodelingunivariatemultimodal,
      title={Statistical Modeling of Univariate Multimodal Data}, 
      author={Paraskevi Chasani and Aristidis Likas},
      year={2024},
      eprint={2412.15894},
      archivePrefix={arXiv},
      primaryClass={cs.LG},
      url={https://arxiv.org/abs/2412.15894}, 
}
