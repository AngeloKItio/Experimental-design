# Experimental-design
Most individuals continue their education after high school by enrolling in colleges. Undergraduate students are constantly faced with expenses such as tuition, fees, and room and board costs. The data set I study provides a state-by-state breakdown of the average cost of undergraduate education in the United States. This is dependent on a number of variables, including the state, the type of university (private, in-state or out-of-state), the program's length, and others. If a student's status falls under one of these conditions, the data set will provide an overview of the amount that they should expect to pay. Due to this, our research is significant for both existing and upcoming undergraduate students, as well as for their parents and other interested parties.

The dataset, which has 3548 entries and 6 columns with no missing values can be accessed with the following link: Average cost of undergraduate student by state USA

Knowing naturally that: generally across the USA, private universities cost more than public universities, I would therefore concentrate on the average costs (fees/Tuition) of public universities, depending on whether the student is at a public-in state or public out of state university. I want to utilize statistical techniques to determine whether there is a significant difference between public in-state institutions and public out-of-state universities in terms of the average cost of undergraduate students. This brings up two hypotheses:

H₀: There is no significant difference between the average cost of undergraduate students in public in-state universities versus that of public out-of-state.

Ha: There is a significant difference between the average cost of undergraduate students in public in-state universities versus that of public out-of-state.

I will firstly produce a data set for this study that only includes records with "Fees/Tuition" as the type of expense. In addition, I'll make two DataFrames, one with all the data for public in-state universities and the other with public out-of-state universities.

I will start the analysis by checking the hypotheses fo the t-test. If the distributions of average cost appear to be close to normally distributed based on their histogram, skewness, and kurtosis, I will conduct an independent samples t-test between the groups at the two-tail, 95% confidence interval. If not, I will conduct a non-parametric test between the groups.

I will finish up my analysis, and then I'll decide whether or not to reject the null hypothesis.

Students frequently find that their "dream" universities are not located in the states where they live. If picking out-of-state public universities over those in-state would pay off for students and even parents, the answer to this research question will provide some useful information.

​
