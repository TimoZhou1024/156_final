# STAT 156: Project Description

# 1 Assignment Description

The goal of this assignment is to apply learned methods from this course to analyze real- world datasets and critically appraise causal claims made in academic publications. This project is a group assignment with each group consisting of no more than two students.

It is strongly recommended that students replicate and re-analyze the results of an academic paper whose original datasets or similar datasets are publicly available. Datasets provided by authors on the publication website are cleaned already and should match the authors published results exactly, so please do not use the cleaned datasets on the publication website unless the paper is an experimental study. As a part of the replication exercise, you and your group should download the original dataset and clean it to approximately match the sample selection used in the published paper. For other forms of final project assignments, such as a literature review with simulation studies to compare multiple methods, please attend the GSI's office hour.

# 2 Submission Instructions

Every group must submit a copy of the assignment from their group in the pdf file on Gradescope and indicate the group members. The final project is due at 11:59 pm PT on Gradescope on December 12th. No late submissions are allowed. For all written assignments, please attach the code for analysis at the end. The code attachment does not count toward the page limit.

The title of the submission should include your group number and your initials. Assignments must be typed. Each writeup submission must have your group number and your names, include a brief centered title, use an 11 or 12-pt font, 1.5 or double spacing, use a 1-inch margin on all sides.

You are welcome to use either R or Python for your final project. For all codes, please use a good coding style and comment on the code so it is readable.

# 3 Suggested Structure of the Writeup

The final project writeup should be understood as a formal replication paper that is ready to be submitted to a journal. Our suggested structure of the writeup contains the following parts:

# 3.1 Paper summary and summary statistics table

This part should complete the following tasks:

1. Summarize the paper's research question and its answer;  
2. Describe the datasets used in answering the question;  
3. Clean the dataset;  
4. Replicate and interpret a summary statistics table that presents distributional characteristics (mean, median, IQR, etc) of key variables and covariates used in the empirical analysis.

Note: The summary table need not replicate exactly as the table produced in the paper. They say that  $90\%$  of the effort in an observational empirical paper is cleaning the data. It is fine if you are not able to clean the data exactly as described in the paper.

# 3.2 Replicate the main results

This part should complete the following tasks:

1. Describe the empirical method in identifying the causal effect (for instance, whether the researchers conduct a randomized experiment or use policy changes to answer their research questions) and state their assumptions for identifying the causal effect clearly in both English and mathematics  
2. Replicate the main result of the paper and interpret it in English  
3. Critically appraise the stated assumptions for causal identification. For instance, if the paper is carrying out an experiment, consider whether the experiment is balanced or if it achieves the stated goal of the author. If the paper is using a policy change or another form of "natural experiments", consider whether there would be confounding factors.

# 3.3 Replicate robustness checks/extensions

In economic and other social sciences, after the main result, there will be a section titled "Robustness Checks" in papers about observational studies or "Extensions" in papers about experimental studies. The purpose of these sections is to convince readers that the main result holds up against various critiques on the identification assumption, or to illustrate subtleties in interpreting the main result. The writeup should complete the following:

1. Pick at least one of the robustness checks or extensions from the paper and replicate it;

2. Include a writeup explaining what the robustness check or extension achieves.

# 3.4 Re-analyze

This part should complete the following:

1. Re-analyze the main result in the paper using methods taught in this class (for example, IPW estimators treatment effect bounds, Fisherian rerandomization tests);  
2. Justify why these methods can be applied to the setting in the paper;  
3. Compare and contrast your findings with the main result. If the results differ significantly, conjecture or analyze the source of discrepancies.

# 4 Where to Find Academic Papers for Replication

# 4.1 Economics

It is common for students to replicate papers from the American Economic Association as the Association has required authors to upload datasets and code (if it can be shared publicly) beginning in 2005. In particular, we recommend students look for empirical papers in the American Economics Review, American Economic Journal: Applied Economics, or American Economic Journal: Economic Policy. Three other major outlets for empirical papers in economics that have adopted data-sharing policies within the past five years are the Quarterly Journal of Economics, Journal of Political Economy, and Journal of Labor Economics.

# 4.2 Epidemiology and Biostatistics

Top journals in epidemiology and biostatistics include: Biostatistics, Biometrics, American journal of Epidemiology, Statistics in Medicine, Statistical Methods in Medical Research, PLOS ONE Epidemiology, etc.

# 4.3 Others

Top journals in sociological and political science that have also adopted and enforced the data sharing policies are American Journal of Political Science (since 2014) and Sociological Methods & Research (since 2009).

# 5 Where to Find Public Datasets

- ICPSR - a user-supported data repository at the University of Michigan that contains thousands of datasets. Most major universities subscribe to ICPSR and datasets are downloadable from the website after registration.  
- IPUMS - a data repository at the University of Minnesota that contains harmonized census and survey datasets from around the world.  
- Panel Study of Income Dynamics - the longest running longitudinal household survey in the world, abundantly used by social scientists.  
- National Longitudinal Survey of Youth - longitudinal data of young adults, also commonly used by social scientists.  
- National Health and Nutrition Examination Surveys - a health study commonly used in epidemiology and public health.  
- Harvard Dataverse - a code and data repository for a broad selection of academic papers. When using the Dataverse, be careful to find data that is not already cleaned.  
- Home of US Government's open data - Many US Government's open data set. For example, there are many Financial data sets on data.gov.  
- Applied Econometrics Data Archive.

# 6 Suggested (Observational Studies) Papers for Replication

- Daron Acemoglu and Joshua D. Angrist, “Consequences of Employment Protection? The Case of the Americans with Disabilities Act”, Journal of Political Economy, 2001  
- Daron Acemoglu, David H. Autor and David Lyle, "Women, War and Wages: The Effect of Female Labor Supply on the Wage Structure at Mid-Century", Journal of Political Economy, 2004  
- Elizabeth O. Ananat, “The Wrong Side(s) of the Tracks: The Causal Effects of Racial Segregation on Urban Poverty and Inequality”, American Economic Journal: Applied Economics, 2011  
- Maximilian Auffhammer and Ryan Kellogg, “Clearing the Air? The Effects of Gasoline Content Regulation on Air Quality”, American Economic Review, 2011

- Patricia Cortes and Jose Tessada, “Low-Skilled Immigration and the Labor Supply of Highly Skilled Women”, American Economic Journal: Applied Economics, 2011  
- David Deming, "Early Childhood Intervention and Life-Cycle Skill Development: Evidence from Head Start", American Economic Journal: Applied Economics, 2009  
- Daniel K. Fetter, “How Do Mortgage Subsidies Affect Home Ownership? Evidence from the Mid-Century GI Bills”, American Economic Journal: Economic Policy, 2013  
- Alexander M. Gelber, “How Do 401(k)s Affect Saving? Evidence from Changes in 401(k) Eligibility”, American Economic Journal: Economic Policy, 2011  
- Jonathan Gruber and Samuel A. Kleiner, “Do Strikes Kill? Evidence from New York State”, American Economic Journal: Economic Policy, 2012  
- Hilary W. Hoynes and Diane Schanzenbach, "Consumption Responses to In-Kind Transfers: Evidence from the Introduction of the Food Stamp Program", American Economic Journal: Applied Economics, 2009  
- David S. Johnson, Jonathan A. Parker and Nicholas S. Souleles, “Household Expenditure and Income Tax Rebates of 2001”, American Economic Review, 2006  
- David S. Johnson, Robert McClelland, Jonathan A. Parker and Nicholas S. Souleles, "Consumer Spending and the Economic Stimulus Payments of 2008", American Economic Review, 2013  
- Melissa S. Kearney and Phillip B. Levine, “Early Childhood Education by Television: Lessons from Sesame Street”, American Economic Journal: Applied Economics, 2019  
- Jeanne Lafortune, “Making Yourself Attractive: Pre-marital Investments and the Re- turns to Education in the Marriage Market”, American Economic Journal: Applied Economics, 2013  
- Phillip B. Levine, Robin McKnight and Samantha Heep, "How Effective Are Public Policies to Increase Health Insurance Coverage among Young Adults?", American Economic Journal: Economic Policy, 2011  
- Gianmarco Ottaviano, Giovanni Peri and Greg C. Wright, "Immigration, Offshoring and American Jobs", American Economic Review, 2013  
- Albert Saiz and Susan Wachter, "Immigration and the Neighborhood", American Economic Journal: Economic Policy, 2011

- Betsey Stevenson and Justin Wolfers, "Bargaining in the Shadow of the Law: Divorce Laws and Family Distress", Quarterly Journal of Economics, 2006  
- Li, Liang, and Tom Greene, "A weighting analogue to pair matching in propensity score analysis", The International Journal of Biostatistics, 2013  
- Baiocchi, Michael, Jing Cheng, and Dylan S. Small, "Instrumental variable methods for causal inference", Statistics in Medicine, 2014  
- Kurth, Tobias, Alexander M. Walker, Robert J. Glynn, K. Arnold Chan, J. Michael Gaziano, Klaus Berger, and James M. Robins, "Results of multivariable logistic regression, propensity matching, propensity adjustment, and propensity-based weighting under conditions of nonuniform effect", American Journal of Epidemiology, 2006  
- Franklin, Jessica M., Wesley Eddings, Peter C. Austin, Elizabeth A. Stuart, and Sebastian Schneeweiss, "Comparing the performance of propensity score methods in health-care database studies with rare outcomes", Statistics in Medicine, 2017  
- Austin, Peter C., and Elizabeth A. Stuart, “Moving towards best practice when using inverse probability of treatment weighting (IPTW) using the propensity score to estimate causal treatment effects in observational studies”, Statistics in Medicine, 2015