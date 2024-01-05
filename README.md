# ACCORD_KFRE

This repository contains code to reproduce the results presented in the paper 

> **Charu V, Liang JW, Chertow GM, Li ZJ, Montez-Rath ME, Geldsetzer, P, de Boer IH, Tian L, Kurella Tamura M. (2024). Heterogeneous Treatment Effects of Intensive Glycemic Control on Kidney Microvascular Outcomes and Mortality in ACCORD.**
  
## R package dependencies
- Data wrangling and visualization: [`tidyverse`](https://cran.r-project.org/web/packages/tidyverse/index.html), [`zoo`](https://cran.r-project.org/web/packages/zoo/index.html), [`ggrepel`](https://cran.r-project.org/web/packages/ggrepel/index.html), and [`survminer`](https://cran.r-project.org/web/packages/survminer/index.html)
- Model fitting and evaluation: [`survival`](https://cran.r-project.org/web/packages/survival/index.html), [`survRM2`](https://cran.r-project.org/web/packages/survRM2/index.html), [`nlme`](https://cran.r-project.org/web/packages/nlme/index.html), and [`mvnfast`](https://cran.r-project.org/web/packages/mvnfast/index.html)
- Parallelization: [`foreach`](https://cran.r-project.org/web/packages/foreach/index.html) and [`doParallel`](https://cran.r-project.org/web/packages/doParallel/index.html)

## Data
- Action to Control Cardiovascular Risk in Diabetes (ACCORD) study data<sup>[1](#myfootnote1), [2](#myfootnote2)</sup>

## Repo navigation

- `kfre.Rmd` and `kfre.html`: Reproduce Figures 1-4, S1-S5, S9, and S12-S13 and Tables 1-2. 
- `eGFR_slopes/eGFR_slopes.Rmd` and `eGFR_slopes/eGFR_slopes.html`: Reproduce Figures S6-S8 and Table S1. 
- `baseline_UACR/baseline_UACR.Rmd` and `baseline_UACR/baseline_UACR.html`: Reproduce Figure S10 and Table S2. 
- `baseline_eGFR/baseline_eGFR.Rmd` and `baseline_eGFR/baseline_eGFR.html`: Reproduce Figure S11 and Table S2. 

---

<a name="myfootnote1">1</a>. Action to Control Cardiovascular Risk in Diabetes Study Group, Gerstein HC, Miller ME, et al. Effects of intensive glucose lowering in type 2 diabetes. *N Engl J Med*. 2008;358(24):2545-2559. doi:10.1056/NEJMoa0802743

<a name="myfootnote2">2</a>. Ismail-Beigi F, Craven T, Banerji MA, et al. Effect of intensive treatment of hyperglycaemia on microvascular outcomes in type 2 diabetes: an analysis of the ACCORD randomised trial. *Lancet*. 2010;376(9739):419-430. doi:10.1016/S0140-6736(10)60576-4
