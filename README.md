# Baltimore-Crime-Rate
Aim: 

In the subsequent phases, the project ventures into the intricate interplay between neighborhood 
dynamics and crime rates in Baltimore. The overarching goal is to hypothesize connections among 
factors such as vacant building notices, rehabilitation initiatives, and gun offender registries. The 
aim is twofold: to discern whether these elements exert positive or negative influences on crime 
rates and to unravel unexpected insights that could reshape our comprehension of urban dynamics 
and their profound impact on community safety. 



Tools Required:

Online 

 Google Collab (Suggested)


Offline

 Python Software 

 Anaconda Navigator 

  *** Jupyter Notebook


Procedure 

STEP1:	Datasets

Part 1 Crime Data
This dataset represents the location and characteristics of major Part 1 crime against persons such as homicide, shooting, robbery, aggravated assault etc. within the City of Baltimore.

Vacant building notices
This dataset represents the Vacant Buildings Notices located throughout the City of Baltimore.

Vacant building rehabs
This dataset represents the location of vacant buildings rehabs located throughout the City of Baltimore.

Gun Offender Registry
This dataset represents the Gun Offender Registry for persons convicted of at least one gun-related offense and are required to register their name and address with police; also required to check-in with police every 6 months for three years.

BPD Arrests
This dataset represents arrests made by the Baltimore Police Department.



3.	Data Preprocessing and Cleaning
	
In the data preprocessing and cleaning phase of the project, we initiated by extracting the unique values of the neighborhoods, ensuring uniformity by converting them to lowercase and trimming any unexpected spaces. This step sets the foundation for a consistent and standardized representation of neighborhood data.

Subsequently, we streamlined the dataset by dropping columns that were deemed unnecessary for our analysis while ensuring that the order of the remaining columns in the Neighborhood Data was maintained. This process helps declutter the dataset and retains relevant information for further investigation.

Focus was placed on filtering the data to cover the period from 2017 to 2020, specifically targeting incidents related to violent crimes. This filtering ensures that our analysis homes in on the relevant timeframe and crime types, laying the groundwork for meaningful insights.

Further, we engaged in the grouping of data, categorizing it by both Year and Neighborhood. The total incidents of specified crimes were then summed within these groupings, facilitating a more aggregated view of the data. The outcome was the creation of a two-dimensional array representing all incidents from 2017 to 2022, providing a comprehensive overview of the crime landscape over this period.

In pursuit of understanding the dynamics of crime changes across neighborhoods, we embarked on extracting and creating separate data frames for areas experiencing increasing and decreasing crime rates. The differentiation enables a focused analysis of trends and patterns within specific subsets of the data. 




3. Visualization:

Creating and representing the visualizations which is important in the code I have implemented 
other visualizations too please check it.
Employed the Matplotlib library to create visualizations for a better understanding of crime 
trends.
Utilized bar charts to illustrate the crime counts for specific neighborhoods and line graphs 
to depict changes over the years.
Statistical Analysis:
Calculated crime rate changes between consecutive years and percentage changes for 
selected neighborhoods.
Evaluated the overall change in crime rates across all neighborhoods.




4. Hypothesis Testing:

Hypothesis testing is a statistical technique that allows us to draw conclusions about population parameters by analyzing a sample of data. The process entails the development of hypotheses, the gathering and examination of data, and the formulation of conclusions on the population based on the observed sample. Hypothesis testing is an essential element of the scientific method and serves as a crucial factor in empirical research conducted in diverse disciplines.

Key Components of Hypothesis Testing: 

The null hypothesis (H0):

The null hypothesis is a declarative statement asserting the absence of any impact, distinction, or alteration in the population parameter.
H0, or the null hypothesis, describes the existing state of affairs and posits that any observed disparities are attributable to chance or sample fluctuations.
Usually consists of assertions of equivalence, such as the equality of population means.

Alternate hypothesis (H1 or Ha):

The alternative hypothesis is a proposition that opposes the null hypothesis, indicating the presence of an effect, distinction, or alteration.
H1 or Ha is the symbol used to signify the assertion or hypothesis that researchers strive to substantiate with evidence.
The comparison might be unilateral (more than or less than) or bilateral (not equal to).

Alpha (α) is a statistical term that represents the significance level.

The significance level (α) represents the probability of erroneously rejecting the null hypothesis when it is indeed true.
Typical options include 0.05, 0.01, or 0.10.
α is the parameter that establishes the level at which statistical significance is determined.

Statistical Test and Probability Distribution:

The selection of a test statistic is contingent upon the nature of the data and the hypothesis under examination.
Typical test statistics comprise t-tests, z-tests, chi-square tests, and F-tests.
The chosen test statistic adheres to a certain probability distribution, such as the t-distribution or normal distribution.

P-value:

The p-value represents the likelihood of receiving outcomes that are as extreme as the observed results, on the assumption that the null hypothesis is correct.
A low p-value indicates strong evidence against the null hypothesis.
P-values facilitate the determination of whether to reject or retain the null hypothesis.

Conclusion:

Assess the p-value in relation to the significance level:
If the p-value is less than the significance level α, then the null hypothesis should be rejected.
If the p-value is greater than or equal to the significance level (α), then we do not have enough evidence to reject the null hypothesis.
The judgment is made by evaluating the robustness of the evidence against the null hypothesis.


5: 

In formulating the hypothesis, considering variables such as vacant building notices, vacant 
building rehabs, and the Gun Offender Registry. The objective is to investigate whether these 
factors exert any influence on the fluctuations in crime rates within the identified neighborhoods 
and citywide. This comprehensive analysis aims to discern patterns and correlations, shedding 
light on the potential impact of these specific elements on the dynamic landscape of crime in 
Baltimore. 


This analytical process entails a systematic approach, involving the meticulous filtering of relevant 
columns, grouping the data by year and neighborhood, and subsequently calculating the 
differences in counts from 2017 to 2022. Moreover, computing the percentage change for each 
identified factor—vacant building notices, vacant building rehabs, and the Gun Offender Registry. 
Through these rigorous steps, the aim is to unravel meaningful insights into the potential 
correlation between these factors and the changes in crime rates over the specified timeframe. 

6: 

The subsequent phase of this investigative journey involves the systematic sorting of 
neighborhoods based on the calculated differences in counts. Following this sorting process, the 
focus will shift to the meticulous selection of the top five and bottom five neighborhoods. This 
strategic approach aims to spotlight specific geographic areas that exhibit notable variations in 
factors such as vacant building notices, rehabs, and gun offender data. By honing in on these 
extremes, the group seeks to uncover nuanced patterns and potential correlations within 
Baltimore's urban landscape. 


7: 

In the subsequent phase of our exploration, the focus shifts to visualization, starting with the 
presentation of data related to vacant building notices. This visualization endeavor aims to provide 
a clear and insightful depiction of how vacant building notices vary across neighborhoods and over 
the specified timeframe. By employing visual elements, the group intends to convey nuanced 
patterns, trends, and potential correlations within Baltimore's urban fabric. This visual 
representation serves as a crucial tool in fostering a deeper understanding of the dynamics between 
vacant building notices and changes in crime rates. 
The coming visualizations show various representations of the hypothesis made. 
The visualizations which were made was taken based on the datasets used and various testings 
performed. 






Conclusion: 

In unraveling Baltimore's crime tapestry, our analysis of diverse datasets spotlighted temporal 
crime shifts, scrutinized vacant building dynamics, and delved into the Gun Offender Registry's 
impact. Visual storytelling painted nuanced crime portraits, spotlighting fluctuating trends and 
high/low-performance neighborhoods. Statistical tests added precision, demystifying 
correlations. Despite limitations, this analysis ignites actionable insights, fueling targeted 
interventions. 

Following the analysis of Baltimore's crime landscape, our findings present an 
intricate narrative. The interplay between vacant building notices, rehabilitations, and crime rates 
remains elusive, lacking statistically significant correlations. However, a noteworthy revelation 
emerges concerning the Gun Offender Registry, indicating a substantial correlation with shifting 
crime dynamics. The observed positive link suggests that heightened gun offender counts may 
contribute to rising neighborhood crime.

Policymakers and law enforcement should heed this 
insight, focusing on targeted initiatives for supervision and violence prevention within this 
demographic. While further research, incorporating socioeconomic nuances, promises deeper 
clarity, the current evidence underscores the pivotal role of gun offender registries in shaping 
Baltimore's recent crime trends.
