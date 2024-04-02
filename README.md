
# Business Case: Aerofit - Descriptive Statistics & Probability




## Objective
This repository analyzes customer data for Aerofit, a fitness equipment brand, aiming to understand the target audience for each treadmill product (KP281, KP481, KP781). By examining demographic and behavioral factors like age, gender, education, marital status, usage, income, fitness level, and weekly miles, comprehensive customer profiles are created. Additionally, conditional and marginal probabilities are computed to highlight influential purchasing factors.
## About Data
Aerofit is a leading brand in the field of fitness equipment. Aerofit provides a product range
including machines such as treadmills, exercise bikes, gym equipment, and fitness
accessories to cater to the needs of all categories of people.
### Product Portfolio
* The KP281 is an entry-level treadmill that sells for $1,500.
* The KP481 is for mid-level runners that sell for $1,750.
* The KP781 treadmill is having advanced features that sell for $2,500.

Product Purchase | KP281, KP481, or KP781

| Features | Description |
| :- | :- |
| Product Purchased | KP281, KP481, or KP781 |
| Age | In years |
| Gender | Male/Female |
| Education | In years |
| MaritalStatus | MaritalStatus |
| Usage | The average number of times the customer plans to use the treadmill each week |
| Income | Annual income (in $) |
| Fitness | Self-rated fitness on a 1-to-5 scale, where 1 is the poor shape and 5 is the excellent |
| Miles | The average number of miles the customer expects to walk/run each week |




## Analysis Steps
1. Data Analysis
* Checked dataset structure, data types, and dimensions.
* Identified missing values in each column.
2. Outlier Detection
* Detected outliers using boxplots.
* Handled outliers by clipping data between the 5th and 95th percentile.
3. Effect of Features on Product Purchased
* Explored relationships between categorical variables (marital status, gender) and product purchased with count plots.
* Investigated relationships between continuous variables and product purchased using scatter plots.
4. Probability Representation
* Calculated marginal probability to determine the percentage of customers purchasing each product.
* Found probabilities of purchasing a product based on each column.
* Determined conditional probability, e.g., the likelihood of purchasing KP481 given female gender.
5. Correlation Analysis
* Analyzed correlations between features using a heatmap and correlation function.
6. Customer Profiling and Recommendations
* Developed customer profiles for each treadmill product based on age, gender, and income.
* Provided actionable recommendations based on insights derived from the analysis.
