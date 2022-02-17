# Climate Change Belief - Statistical Analysis Using R

Author: Sarah Choi

## Introduction

With rising global temperatures, the existence of climate change has been a controversial topic. The natural environment is deteriorating; therefore, it is important to understand the population's awareness of climate change. A study called "Pulse of the Nations", conducted by Card's Against Humanity, examines whether a person believes in climate change along with many other factors. 

In this observational study, we want to examine the relationship between whether or not someone believes in climate change depending on their political views and socioeconomic status. How do political views, income, and education level affect someone's views on climate change?

  1. What are the relationship between belief in climate change and political views (party and trump_binary)? 
  2. What are the relationship between belief in climate change and economic status (education and income)?

To conduct this research, we will be using the survey data from the "Pulse of the Nations." This study has a sample size of 785 people and measures 17 variables; these factors can be found in the data set below. The DK/REF responses were omitted from the raw survey data to simplify the data set; we will be using the clean survey data for this study. We will be using trump_binary (rather than trump_approval) to conduct logistical regression and model probability relationships; the "Neither approve nor disapprove" category was defined as "Disapprove" because only the people that clearly approve Trump was put into the "Approve" category. 

According to [The U.S. Census Bureau](“https://www.census.gov/library/publications/2020/demo/p60-270.html”), the median household income was $68,703 in 2019. For the purpose of the study, an income above $68,703 will be considered high income. The standard of advanced education would be post-secondary education (college and above). These standards will be used for understanding the relationship between an individual's belief in climate change and socioeconomic status. It is important to note that the standards of high income and advanced education are unique to this study and its analysis; this may be different in other studies. This is an observational study. 

## Conclusion
Upon analysis, we can conclude: 

  1. When controlling for political party, individuals who approve of Trump have a lower climate change belief. Democrats who disapprove of Trump are 57% more likely to believe in climate change than Republicans who approve of Trump.  
  2. Individuals who believe in climate change had higher incomes, between roughly $3619 to $33610 more (95% confident), compared to those who do not. This finding is statistically and practically significant.
  3. Education level did not show a significant trend with climate change belief (when using a college degree as standard for comparison and controlling income).  
