### A/B testing target:

to see which version plays better

### A/B testing step:
- Fix some version
- All users are divided into two (or several) groups
- Detect and resolve problems in the data 
     - Missing Value, Outliers, Unexpected Value
- Look summary stats and plots
- Apply hypothesis testing and check assumptions
     - Check Normality & Homogeneity
     - Apply tests 
          - test normality/parametric: Shapiro Test
          - test homogeneity of variances: Levene Test
          - if normality:
               - and if homogeneity of variances:
                    - independent two-sample t-test
               - if not homogeneity of variances:
                    - Welch Test
          - if not normality/non-parametric:
               - Mann Whitney U Test
- Evaluate the results/ Measure metric for some period
- Make inferences
- Recommend business decisions to your customer/director/CEO etc.

### A/B testing exercise:
|No.| Project |
|---|---------|
|1|[Test effect of site version](https://github.com/Notrew/AB-tesing-exercise/blob/main/scr/AB_testing_for_site_version.ipynb)|
|2|[Test effect of ads showing](https://github.com/Notrew/AB-tesing-exercise/blob/main/scr/AB_testing_for_showing_ads.ipynb)|
|3|[Test effect of game version](https://github.com/Notrew/AB-tesing-exercise/blob/main/scr/AB_testing_for_game_version.ipynb)|
|3|[Test effect of web interface](https://github.com/Notrew/AB-tesing-exercise/blob/main/scr/AB_testing_for_web_interface.ipynb)|


