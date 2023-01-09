# ClaimsDataAnalysis
Exploring claims data using pandas, matplotlib, numpy


## Load data
import pandas as pd
import matplotlib.pyplot as plt

claim = pd.read_csv('https://raw.githubusercontent.com/hdougt29/ClaimsDataAnalysis/main/ClaimsData.csv')
claim.head()
     
age	alzheimers	arthritis	cancer	copd	depression	diabetes	heart.failure	ihd	kidney	osteoporosis	stroke	reimbursement2008	bucket2008	reimbursement2009	bucket2009
0	85	0	0	0	0	0	0	0	0	0	0	0	0	1	0	1
1	59	0	0	0	0	0	0	0	0	0	0	0	0	1	0	1
2	67	0	0	0	0	0	0	0	0	0	0	0	0	1	0	1
3	52	0	0	0	0	0	0	0	0	0	0	0	0	1	0	1
4	67	0	0	0	0	0	0	0	0	0	0	0	0	1	0	1
