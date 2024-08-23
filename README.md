# Final_Dissertation - Unfolding Sudan Civil War: A Remote Sensing Study of Conflict Fires


Adding Google Earth Engine Link - 
FIRMS Data collected Year wise -https://code.earthengine.google.com/7dd6784b02b521e0d46a6e7005cb18af


ACLED Data Collected year wise - https://code.earthengine.google.com/49dd850735adc66a24cc89c646541845 - For Data here Fiiltered ACLED data is used which is available in the Python Notebook data folder.

**ABSTRACT**

Conflicts and wars are unfortunate realities in today's complex and interconnected geopolitical landscape, making real-time monitoring and analysis of these events absolutely critical. Remote sensing technology can revolutionize how we observe and respond to such crises. This study demonstrates the application of remote sensing in conflict monitoring, specifically focusing on the use of fire as a weapon during conflicts. The study centers on Sudan, a nation grappling with over two decades of civil war, which escalated significantly in 2023, resulting in a large-scale humanitarian crisis.

This study has two key aims: to identify conflict-induced fires using remotely sensed **FIRMS** fire raster data and **ACLED** conflict data, and to develop a robust modeling approach for predicting conflicts when ACLED data is unavailable. 

By analyzing historical (2000-2022) and conflict-specific (2023) FIRMS fire data, the study estimated an optimal **z-score** threshold of 0.019719 for distinguishing conflict-induced fires from regular fire (e.g. agricultural, industrial, forest fire etc.). The optimal z-score threshold is applied to predict conflicts in Sudan’s war zone, and the results are compared with the actual conflicts data from ACLED. The classification achieved a recall score of 71.5% indicating a better than expected performance in identifying conflicts. However, precision remains low at 34.9% and F1 score moderate at 46.9%, highlighting the challenge of false positives.

The second part of the study focused on using FIRMS fire data to predict violent conflict events in the absence of ACLED data. Five panel data regression methods were tested. The results of regression analysis strongly indicate the positive correlation between conflicts (dependent variable, y) and fire count (independent variable, X). All 5 models examined produced statistically significant (p-value < 0.05) results with positive coefficients and F-statistics, confirming a strong relationship between fires and conflicts. 

The **Fixed Effects Model** with entity and time controls emerged as the most effective model, demonstrating statistically significant results, better handling of residual correlations, normality and heteroskedasticity. The model confirms a positive correlation between fire counts and conflicts, with a 1% increase in fire count resulting in a 0.0157% increase in conflict count.




This study underscores the global potential of FIRMS fire data for monitoring conflict zone. The approach is particularly valuable for real-time monitoring in remote or restricted areas, such as Sudan, and scalable owning to global availability of underlying FIRMS and ACLED data.



**DATA** is in the gitignore file. If need an access please contact [me](https://www.linkedin.com/in/sameerasiddiqui/)
