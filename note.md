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
- Recommend business decision to your customer/director/ceo etc.