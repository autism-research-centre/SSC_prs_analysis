# SSC_prs_analysis

## Basic code for PRS analysis (in progress)

### analysis for cases

```bash

./plink --bfile SFARImergedall --filter-cases --make-founders --indep-pairwise 100 50 0.2 --out casespca --threads 20

./plink --bfile SFARImergedall --exclude casepca.prune.out --make-founders --filter-cases --pca --out SSC_cases_pca --threads 20

```
