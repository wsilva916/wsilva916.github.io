<div style="background-color:#103783; padding:20px; border-radius:5px; color:white; font-size:36px;">
<strong>Data Science and Analytics Portfolio</strong>
</div>
### *Warren Silva | Sacramento, CA* | [LinkedIn Profile](https://www.linkedin.com/in/warren-silva/)

---

<div style="background-color:#9BAFD9; padding:10px; border-radius:5px; color:white; font-size:24px;">
<strong>Python Projects</strong>
</div>

### [A/B Test for Retail Website Promotion Groups](https://nbviewer.org/github/wsilva916/wsilva916.github.io/blob/main/retail_site_ab_test.ipynb)
- Analyzes two groups of site visitors offered different promotions, to determine the impact on:
  - Likelihood of making a purchase
  - Average spend when a purchase is made   
- Many important factors and decision points are assessed programmatically, including:
  - Classification of the target variable as **binary** or **continuous**
    - For binary target variables, the size of the sample(s) determines the most appropriate independence test, between **Chi-Square test** or **Fisher's Exact Test**    
  - For continuous target variables, there are several decision points:
    - The size of the sample(s) is used to determine the most appropriate normality test, between **Shapiro-Wilk** or **Kolmogorov-Smirnov**
    - Normality test results are used to determine if **Levene's Homogeneity of Variance Test** is needed
    - The appropriate group difference test is determined by the combination of the normality test and variance test (where applicable), and could be a **Two-Sample T-Test**, **Welch's T-Test**, or the **Mann-Whitney U Test**

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
