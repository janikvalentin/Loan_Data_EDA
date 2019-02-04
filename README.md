
## Project Overview

For this project I analyze a loan dataset containing 105.000 rows and 21 columns
from the peer-to-peer loan marketplace [Prosper](https://www.prosper.com/about).

The most important files include
- wrangle_exploration_act.ipynb: a notebook documenting wrangling efforts and an
exploratory investigation of the dataset to work out the direction of the explanatory report.
- findings_report.html: an explanatory report of credit default rates.
- findings_report-code_visible.html: same report as above with code cells visible
so you can get an insight into how each graph is created.

## Technologies Used
- Python
- Libraries: numpy, pandas, matplotlib, seaborn, plotly
- report is written in jupyter notebook and exported to html

## Key Findings
- The probability of a loan to get charged off varies greatly for different credit ratings.
- Credit default rates vary by up to 30 percent regarding the reason specified by the borrower
to take on a loan.
- Dentists and judges were found to be the most reliable borrower occupations, homemakers and
community college students on the other hand the on average least reliable considering loan payback rates.
- Borrowers with past delinquencies are also less likely to pay back their current loan.
- Loans taken by borrowers specifying their employment status as 'other' are most Likely
to get charged off.
- The mean chargedoff rates differ by up to 20 percent among federal states.
- Prosper increased their commission on every loan by 100 percent within 5 years.
