# Jamboree-Education---Linear-Regression
Jamboree has helped thousands of students like you make it to top colleges abroad. Be it GMAT, GRE or SAT, their unique problem-solving methods ensure maximum scores with minimum effort. They recently launched a feature where students/learners can come to their website and check their probability of getting into the IVY league college.

**EDA Insights**
Those who did research has high chance of admit.
From visualization and correlation factor CGPA,TOEFL and GRE score looks like high correlation.
SOP and LOR has high correlation which is visually visible and also correlation value from heatmap also support the statement.
For university rating 5, those who has GRE score more than 300 and TOFEL score more than 100 has high chance to get admit.
Insights based on stats models

Residual mean of model is zero and also Homoscedasticity is also there.
Independent error is lesser than 2 which proves statistically positive correlation.
Pvalue of University Rating and sop is greater than 0.05 which proves statistically which has high correlation.
From visualization, correlation factor TOEFL Score almost linear relationship with GRE Score and also GRE Score close to vif value of 5. Based on Domain knowledge TOEFL Score is best choice to drop from the data.

**Insights based on stats final models**

Residual mean of model is zero and also Homoscedasticity is also there.
Independent error is lesser than 2 which proves statistically positive correlation.
Residual error almost has gaussian distribution which is visibile by qq plot and kde plot.
By droping columns R2score drop by 1% which is negligible since our model becames much simpler.
Insights and Recommendation
From two models(one with all columns and one with selected columns) has almost equal metrics which helps to design our model is simple and also performs well as equal first model.
More the GRE score, CGPA and LOR, more the chance of admit.
We need more datasets based on chance of admit from 0.5 to 0.8 where error value is high compared to other.

**Recommendations**

Based on customer's LOR score, CGPA score, GRE score, we can suggest appropriate rating of selected university
With this model, we can auto chat bot so that customers wont need to wait get information and with our model and chat bot system they will get list of universities.
With this approach and we can create a model not only for us based universities but also to European and Canadian universities.
