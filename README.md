# project_2

# Overview

This aim of this project is to find out how general economic performance metrics (GDP and major stock index performance) are correlated with wages in Spain. 


<br>

# Requirements/Libraries Used:
This code was written in Python/Jupyter Notebook, using the following libraries:
<br>
- Numpy
- Pandas
- matplotlib.pyplot
- Seaborn

<br>
 

# Hypotheses:
<br>

## 1- As GDP grows, wages and purchasing power grow

<br>

![year_plot](https://github.com/victorbescos/project_2/blob/0928de08c6bbf42ad6c71af301f72cfcf3b8118f/GDP_plot.png)

This plot shows Nominal and Real GDP growth in Spain over the last 20 years. The raw data was extracted from the ECONDB API. From the plot we can observe that the size of the Spanish economy as measured by GDP has grown substantially (practically doubled) both in nominal and real terms. 

<br>

The following plot shows the evolution of Nominal and Real Mean Salary in Spain. The nominal salary data was extracted from a INE (Instituto Nacional de Estadística) dataset. In order to estimate real salary (adjusted for inflation), I extracted CPI information for Spain from the ECONDB API. I established 2002 as the baseline year and performed a calculation that transforms Nominal into Real Salary based on every year's CPI in relation to the baseline year CPI. 

![year_swarm](https://github.com/victorbescos/project_2/blob/0928de08c6bbf42ad6c71af301f72cfcf3b8118f/Salaries_plot.png)


CPI has limitations as an indicator of inflation rate but it is effective in capturing the changes in purchasing power for the average household. As seen in the plot, the typical Spanish worker now has roughly the same purchasing power that a typical Spanish worker had 20 years ago, even though the economy has substantially grown. 

<br>

The following plot shows the comparison of GDP growth per year vs Real Salary growth per year 

![yearly_growth](https://github.com/victorbescos/project_2/blob/0928de08c6bbf42ad6c71af301f72cfcf3b8118f/GDPvsSalaries_plot.png)


# Conclusion

<br>

It appears that despite the Spanish economy growing substantially over the past two decades, Spanish workers are not experiencing an increase in purchasing power long-term. While average nominal wages are increasing, in real terms (when adjusting for inflation) wages have been stagnant for roughly 20 years. 