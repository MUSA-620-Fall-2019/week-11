# Week 11<br>Supervised Learning in Python

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MUSA-620-Fall-2019/week-11/master?filepath=lecture-11.ipynb)

## Updating your local environment

The `environment.yml` in this repository
contains all of the necessary packages. To update your local environment:

**Step 1.** Download the `environment.yml` file in this repository to your computer.

**Important:** Make sure you download the **raw** version of the file from GitHub and that the file extension on your computer is `.yml`.

**Step 2.** From either the Anaconda Prompt (Windows) or Terminal app (MacOS):

```
conda env update --file environment.yml --name musa-620
```

where `musa-620` should be the same name of the environment you have been using.

## Reference

- scikit-learn
  - [User guide](https://scikit-learn.org/stable/user_guide.html)
  - [RandomForestRegressor](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html)
  - [Column transformer example](https://scikit-learn.org/stable/auto_examples/compose/plot_column_transformer_mixed_types.html)
- [Decision trees](https://towardsdatascience.com/https-medium-com-lorrli-classification-and-regression-analysis-with-decision-trees-c43cdbc58054)
- Machine learning models in the real estate industry
  - [Airbnb recommends pricing to hosts](https://spectrum.ieee.org/computing/software/the-secret-of-airbnbs-pricing-algorithm)
  - [Trulia converts house photos to house features](https://www.trulia.com/blog/tech/image-recognition/)
  - [Zillow's Zestimate](https://www.zillow.com/research/zestimate-forecast-methodology/)
- [The missingno package](https://github.com/ResidentMario/missingno)
- [Presentation on the Office of Property Assessment's methodology](https://www.phila.gov/OPA/Documents/Property%20Assessment%20Methodology.pdf)
- [City Controller analysis of property assessments](https://controller.phila.gov/philadelphia-audits/property-assessment-review/)
- [Algorithmic fairness with case study on modeling Philadelphia's home values](https://urbanspatial.github.io/AlgorithmicFairness_ACodebasedPrimerForPublicSectorDataScientists)
