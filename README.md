# A Cross-national Analysis on Annuity Payments

## Abstract

### Background
The insurance industry exhibits dynamic interactions and imperfect information, which often hinder companies from acquiring comprehensive data on their policyholders. This complexity requires an understanding of numerous risk factors, and insurers can leverage population insights to formulate policies and support national health strategies.

### Objective
This study introduces a mathematical model for creating fair annuity values in life insurance, ensuring sufficient cash flow for beneficiaries upon a policyholder's death. The model employs the Gompertz-Makeham (GM) mortality formula to determine age-related death probabilities and uses commutation functions for streamlined computations. Additionally, a unique cash flow function considers each policyholder's expenses, income, and assets, maximizing their utility.

### Data and Methods
Using data from the Human Mortality Database (HMD) and the Organisation for Economic Co-operation and Development (OECD), we calibrated and tested our model across 41 countries between 1959 and 2020. The results validate the model's applicability for calculating annuity payments, accounting for individual circumstances, life expectancy variability, and fluctuating annual income.

### Results
Results are discussed in detail in the project, including correlations, validations, and the creation of an interest-based 3D model of the annuity.

### Policy Implication
In addition to the model's immediate utility, this study examines the societal aspects of issuing insurance policies, network effects, and potential insights extending beyond traditional risk management.

## GitHub Structure
- **Figures**: All the generated plots and visualizations.
- **Life table Data**: Contains the data related to life expectancy.
- **OECD data**: Contains data related to annual income.
- **processing and visualization.ipynb**: The Jupyter Notebook containing all the data processing and visualization code.

## Authors
Shuyang (Simon) Bian and Yuanyuan Xie.


## Contact
simon.bian@emory.edu and yuanyuan.xie@emory.edu

### Bibliography

1. Castellares, F., Patrício, S., & Lemonte, A. J. (2022). [On the Gompertz–Makeham law: A useful mortality model to deal with human mortality](https://doi.org/10.1214/22-BJPS545). _Brazilian Journal of Probability and Statistics_, 36(3), 613-639.

2. Kirkwood, T. B. L. (2015). Deciphering death: a commentary on Gompertz (1825) ‘On the nature of the function expressive of the law of human mortality, and on a new mode of determining the value of life contingencies’. _Philosophical Transactions of the Royal Society B: Biological Sciences_, 370(1666), 20140379.

3. Federal Reserve Bank of St. Louis. (2022). [Interest Rates, Discount Rate for United States](https://fred.stlouisfed.org/series/INTDSRUSM193N). FRED, Federal Reserve Bank of St. Louis.

4. Slud, E. V. (2001). _Actuarial mathematics and life-table statistics_.

5. Missov, T. I., & Lenart, A. (2013). [Gompertz–Makeham life expectancies: Expressions and applications](https://www.sciencedirect.com/science/article/pii/S0040580913000932). _Theoretical Population Biology_, 90, 29-35.

6. Lagerås, A. N. (2010). Commutation functions under Gompertz--Makeham mortality. _Scandinavian Actuarial Journal_, 2010(2), 161-164.

7. Ogungbenle, M. G. (2022). A theoretical summation-integral scheme involving commutation function in life insurance business. _Ceylon Journal of Science_, 51(2), 147-154.

8. Quinn, S. (2008). The transformation of morals in markets: Death, benefits, and the exchange of life insurance policies. _American Journal of Sociology_, 114(3), 738-780.

9. Campbell, R. A. (1980). The demand for life insurance: An application of the economics of uncertainty. _The Journal of Finance_, 35(5), 1155-1172.

10. Buchardt, K., Møller, T., & Schmidt, K. B. (2015). Cash flows and policyholder behaviour in the semi-Markov life insurance setup. _Scandinavian Actuarial Journal_, 2015(8), 660-688.

