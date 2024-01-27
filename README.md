# stroke_analysis
**A data analysis project on the health and demographic variables related to stroke prediction using Python within a Jupyter notebook.**

**Final Conclusions**
- Despite attempts at oversampling as well as grouping our continuous variables, the binary logistic regression model did not perform well in identifying positive stroke cases
- While this health dataset presented a binary classification problem, the insights gathered from this particular data analysis focused primarily on Exploratory Data Analysis (EDA)
- The following should be areas of focus for both resource allocation for treatment and education of at-risk populations by the ISPA with the long term goal of decreasing stroke occurrence rate -
  - Age and BMI have the highest correlations, odds ratios, and coefficients with our dependent variable of interest (presence of stroke)
  - Those individuals who have heart disease (12.2%) or hypertension (11.3%) demonstrated nearly triple the normal stroke rate (3.8%)
  - 11.2% of seniors, 4.3% of diabetics, and 5.8% of overweight individuals had a stroke; indicating possible relationships
  - Former (6.7%) and current smokers (3.9%) have higher stroke rates as well; indicating a possible relationship
  - Self-employed people had nearly double the stroke rate (7.3%)

**Potential Future Improvements to this Data Analysis**
- Incorporating more robust machine learning models to generate meaningful results
- Larger dataset w/ additional variables (i.e. stress, alcohol intake, or average amount of hours slept) would likely yield additional value
- Geographic data may also offer further insights regarding concentration of stroke by location
