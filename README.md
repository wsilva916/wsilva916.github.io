<div style="background-color:#103783; padding:20px; border-radius:5px; color:white; font-size:36px;">
<strong>Data Science and Analytics Work Samples</strong>
</div>
### *Warren Silva | Sacramento, CA* | [LinkedIn Profile](https://www.linkedin.com/in/warren-silva/)

---

<div style="background-color:#9BAFD9; padding:10px; border-radius:5px; color:white; font-size:24px;">
<strong>Python Projects</strong>
</div>

The Python projects below are presented in Jupyter Notebooks and rendered using [nbviewer](https://nbviewer.org/). Each project includes supporting text, images, as well as code to help both technical and non-technical viewers interpret the program logic and analysis.

### [A/B Test for Retail Website Promotion Groups](https://nbviewer.org/github/wsilva916/wsilva916.github.io/blob/main/retail_site_ab_test.ipynb)

- This analysis evaluates two groups of site visitors offered different promotions to assess their impact on:
  - The likelihood of making a purchase
  - The average spend when a purchase is made   

- Key factors and decision points are assessed programmatically, including:
  
  - Classification of the target variable as **binary** or **continuous**
    - For binary target variables, the sample size determines the most appropriate test of independence, choosing between the **Chi-Square Test** or **Fisher's Exact Test**    
    - For continuous target variables, there are several decision points:
      - The sample size determines the most appropriate normality test, between **Shapiro-Wilk Test** or **Kolmogorov-Smirnov Test**
      - Normality test results determine if **Levene's Homogeneity of Variance Test** is needed
      - The appropriate test for group differences—such as a **Two-Sample T-Test**, **Welch's T-Test**, or the **Mann-Whitney U Test**—is selected based on the combination of normality and variance test results (where applicable)

### [Data Generator for A/B Testing](https://nbviewer.org/github/wsilva916/wsilva916.github.io/blob/main/ab_generator.ipynb)
- Used to generate sample data for project above
- Includes various parameters to control the characteristics of generated data

<div style="background-color:#9BAFD9; padding:10px; border-radius:5px; color:white; font-size:24px;">
<strong>Visualization Projects</strong>
</div>

### [Tableau Dashboard - Airline Reviews](https://public.tableau.com/views/BritishAirwaysReviews_17266156042500/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
- Interactive dashboard featuring:
  - Multiple filters for user-driven insights
  - Selective focus on several different metrics







[Test](https://nbviewer.org/github/wsilva916/wsilva916.github.io/blob/main/cmi-internet-use.ipynb)
