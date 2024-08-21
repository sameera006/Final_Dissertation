# Final_Dissertation - Unfolding Sudan Civil War: A Remote Sensing Study of Conflict Fires


Adding Google Earth Engine Link - 
FIRMS Data collected Year wise -https://code.earthengine.google.com/7dd6784b02b521e0d46a6e7005cb18af


ACLED Data Collected year wise - https://code.earthengine.google.com/3a2487bde210c6fc3aa2aa1690189aea - For Data here Fiiltered ACLED data is used which is available in the Python Notebook data folder.

**ABSTRACT**

With the advancement of technology, particularly in social media platforms and use of remote sensing tools, tracking wars and damage caused all over the world has become significantly easier for providing relief and aid to the survivors.

Remotely sensed earth observation data has been used for informing decisions on environmental hazards arising from changing climate in urban areas, green space coverage, pollution studies, flooding, disaster response and many other applications. Here it is used for monitoring conflicts.  

**The main aim here is to create an open monitoring system which tracks fires and conflict events and can also differentiate between anomalous fires which are supposed to be conflict induced.**

According to the literature , fire is used as the main weapon in conflicts. (Bromley, L. ,2010) Therefore many events link to violence often  lead to outbreak of fires and it can take the form of intentional acts of arson such as the burning of buildings,  accidental ignition of flammable materials due to the use of explosives, burning debris during reconstruction efforts, or the destruction of evidence related to potential war crimes, among other examples and then there are natural fires like forest fire, or man-made seasonal agricultural fires. Most of the researchers working on fire data face difficulties in differentiating between conflict fires and regular fires. Many times, false fires are detected and there are a lot of mismatches between the conflicts reported and fires spotted. (Hamilton and Drake, 2018)  

**Therefore, this study is focused on Sudan crisis which started in April 2023 by two power groups for political reasons and still it is going on. This is the conflict which no one is talking about having less media coverage and attention it’s important to acknowledge this conflict by using remote sensing satellite imagery and google earth engine cloud platform.**

This work focuses on developing an open monitoring system using Fire Information for Resource Management System **(FIRMS)** fire data and Armed Conflict Location & Event Data Project **(ACLED)** conflict data for finding any relation between conflict and fires. The study uses panel dataset which was created by dividing Sudan into grids. Each grid gives the count of fires and ACLED events for 24 years from 2000- 2023. Then multiple **panel data regression methods** is used to identify the best regression model by analyzing the statistical evidence of robustness of underlying methods, such as, coverage of variance, coefficients and statistical significance. The coefficient is positive and statistically significant in all models, indicating that higher fire counts are associated with higher values of ACLED counts. The research looked at 5 regression methods, including, Pooled OLS, Fixed effect (with entity and time control, entity control, and time control), and Random effects model and analyzed the goodness of fit of each model. The **Fixed Effect Model (with entity and time controls)** appears to be the best starting point, given its better handling of residual correlations (lowest Pearson’s correlation) and slightly improved heteroskedasticity and normality.

