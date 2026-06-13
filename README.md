# FLEX Replication

Replication code for **"What's Missing Matters: Negative Feature Attribution for Explainable Classification"**.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KentonWhite/flex-replication/blob/master/flex_replication.ipynb)

## Contents

The notebook reproduces all experiments from the paper:

| Section | Datasets |
|---|---|
| Tabular benchmarks | USArrests, Iris, Wine, Wisconsin BC, Digits, Mice Protein, Anuran, Avila |
| Non-convex boundaries | Two Moons, Concentric Circles |
| Signed attribution | Synthetic exclusion dataset (3-cluster) |
| Negative attribution | Iris setosa case study |

Large-scale benchmarks (20 Newsgroups, CIFAR-10, Covtype) are included as commented-out cells due to runtime.

## Running

Click the **Open in Colab** badge above, then **Runtime → Run all**.

No local installation required. The notebook installs its only non-standard dependency (`ucimlrepo`) automatically.

## Dependencies

`numpy scipy scikit-learn pandas ucimlrepo`
