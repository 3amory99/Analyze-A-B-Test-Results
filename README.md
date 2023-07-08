# Analyze-A-B-Test-Results
Project to analyze A/B test results using python

##  Details 
We will be collaborating on a project that involves analyzing the outcomes of an A/B test conducted by an e-commerce website. The objective is to work through a notebook to assist the company in determining whether they should implement the new page, retain the old page, or potentially extend the experiment duration to arrive at a conclusive decision.

## Libs used
* Pandas
* Numpy
* Random
* Matplotlib
* Statsmodels

## Conclusions
1. P-value for countries is higher than .05, hence countries have no significant influence on conversion rates.
2. P-value for interactions is higher than .05, which suggests that there is no significant influence of landing pages in the US and Canada on conversion rates.
3. The results of this test suggest that the new page doesn't have a higher conversion rate than the old page, so the company shouldn't implement the new page.

Now we are sure that there is no difference between the conversion rate at the old page and the new page and the sample didn't small so the development should continue.
