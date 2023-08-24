# Indian-women-fertility-analysis

## Data:
The dataset originates from the Fiji Fertility Survey and provides information on the number of children ever born to married women of the Indian race. The data classifies these women by:

- Duration since their first marriage (grouped in six categories)
- Type of place of residence (categories: Suva, urban, and rural)
- Educational level (categories: none, lower primary, upper primary, and secondary or higher).
The dataset can be found in the file data.txt. The dataset consists of 70 rows, representing 70 groups of families. Each row provides details for:

- duration: Marriage duration of mothers in each group (in years)
- residence: Residence of families in each group (categories: Suva, urban, rural)
- education: Education of mothers in each group (categories: none, lower primary, upper primary, secondary+)
- nChildren: Number of children ever born in each group (e.g., 4)
- nMother: Number of mothers in each group (e.g., 8).

## Problem:
We aim to determine which factors (duration, residence, education) and their two-way interactions influence the number of children per woman (fertility rate). The observed number of children ever born in each group (nChildren) is contingent upon the number of mothers (nMother) in each group. The disparity in the number of mothers across groups needs to be considered.

## Report Requirements:
Write an analysis report that encapsulates the main findings. The report should:

- Summarize the core conclusions.
- Incorporate highlights from the analysis, including:
- Data visualization
    + Choice of model (e.g., Poisson, binomial, gamma, etc.)
    + Model fitting and selection (e.g., using AIC)
    + Diagnostics
    + Check for overdispersion if necessary
    + Provide a summary/interpretation of the final model.

 The project is done using R.
