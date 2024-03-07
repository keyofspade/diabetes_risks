# diabetes_risks
Objective: Build a model to identify risk factors for diabetes. 

# Intro
With data from the CDC and Behavioral Risk Factor Surveillance System, this model utilizes Logistical Regression to predict the likelihood of diabetes based on independent variables identified during the data processing and analysis.

There are 32 possible variables attributing to diabetes risk classified as either demographic(sex, race, age, etc.), behavioral(physical activity levels, sleep duration, etc.), or medical variables(asthma, kidney disease history, etc.).

According to the CDC's diabetes site, common risk factors for Type I diabetes include having first relatives with Type I diabetes and age. On the other hand, factors of Type II diabetes include being overweight, age, having first relatives with Type II diabetes, and being an African American, Hispanic or Latino, American Indian, or Alaska Native person. There is no differentiation between Type I and Type II diabetes in this dataset, so all independent variables identified are risk factors contributing to increased diabetes risk overall.

# Conclusions Based Upon Logistical Regression:
Some identifiable risk factors for diabetes are:

** Exercise/Activity Outside of Work
** Activity at Work
** General Health
** Age
These independent variables were proven to be significant in their correlation to diabetes as risk factors via statistical tests and analysis, thus suggesting a significant role in diabetes risk prediction. In addition, the distribution of these variables does not suggest other factors skewing the data to be biased, such as time of recent checkup contributing to a timely diabetes diagnosis.

Physical activity level is often one of the most common literature-cited factors of diabetes risk, and this model and analysis support prior research and knowledge. With the prevalence of high sugar, high fat, and high sodium levels in American processed food and culture, individuals considering their health to be fair or good might be less restrictive and less mindful of their diet and physical activity. Age is also a major factor of diabetes risk because individuals have increased Type II diabetes risk due to biological effects of increasing insulin resistance and impaired pancreatic islet function as they age according to the American Diabetes Association.

The model was predicted with 100% accuracy. However, the model could be improved with more data to further evaluate correlation magnitudes between independent variables and diabetes risk.
