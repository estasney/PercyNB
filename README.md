# Percy Notebooks

### Acknowledgments

Special thanks to [Derek Duin](https://www.linkedin.com/in/derekduin/) without whom these notebooks would not have been possible.  

### Table of Contents
1. [Name Data](https://github.com/estasney/PercyNB/blob/master/notebooks/1_name_data.ipynb)
2. [Probability](https://github.com/estasney/PercyNB/blob/master/notebooks/2_probability.ipynb)
3. [Monte Carlo](https://github.com/estasney/PercyNB/blob/master/notebooks/3_monte_carlo.ipynb)

### Run with Binder
These notebooks are interactive! To launch in a live environment click:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/estasney/PercyNB/master)

## What is Diversity Analysis?
In order to achieve the stated goal of a diverse work environment, we need to be able to produce quantifiable measures of diversity. The challenge is that indicators of diversity such as national origin, veteran status, gender, etc. are sensitive and not reported in available datasets.

However, for any population that we wish to analyze we will always have, at a minimum a First and Last name.

In most cultures, there exist 'masculine' and 'feminine' names. However, there is no universal law that requires this. The result is that some names are strong predictors of sex such:

- Elizabeth
- Sarah
- John
- James

While others such as :

- Casey
- Jessie
- Jordan
- Pat

are not strong predictors.               


## Names as Predictors

Based on our own experiences we are likely to agree with the above names and their respective assignments. If our goal is to provide a quantifiable measure, we need some method to determine this.

Let's examine two popular approaches 
   

### Categorical

The categorical approach assigns names to categories based on their tendency to predict a sex. For instance we may see:

- Male : John, James, Jordan
- Female : Sarah, Elizabeth, Casey, Jessie

- Strongly Male: John, James
- Weakly Male: Jordan
- Ambiguous: Pat 
- Strongly Female: Elizabeth, Sarah
- Weakly Female: Jessie

### Probabilistic

The probabilistic approach assigns discrete probabilities of sex for each name. We may see:

- John: 0.05% Female
- Sarah: 99.5% Female
- Jordan: 26.0% Female
- Jessie: 60.2% Female

Percy's diversity analysis is based on probabilistic data. The reasoning will become apparent later. 