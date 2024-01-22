# ClickQuest: Enhancing User Engagement through A/B/n Testing in Library Portal
<img src = "/abn-Test.jpeg">

# Introduction

Small changes on a simple web page can bring various experiences to users, whether positive or negative. Therefore, to test the effects caused by changes in interactivity, A/B testing has become an increasingly utilized tool for interface testing by designers and user experience researchers. In this specific case, we will be working with an extension of the A/B test, where (A) represents the control variable, (B) the treatment variable, and (n) the number 'n' of variables. There is no doubt that A/B testing is a widely used tool to address UX questions.


💻 [Complete Project](https://github.com/JonatasV/abn_test/blob/main/abn_test.ipynb)

📊 [Complete Presentation](https://github.com/JonatasV/abn_test/blob/main/ABN_Test_Presentationpptx.pdf)

# Data Source
The dataset was collected by Google Analytics consists in observations for 5 variations: interact (control), connect, learn, help and services. You can download it here: 

https://scholarworks.montana.edu/xmlui/handle/1/3507

# Analysis Objective
The project aims to address the following hypothesis:

H0: There is no difference between the CTR of the page variants

H1: There is a difference between the CTR of the page variants.

# Methodology
1.	Statistical inference – Chi Squared
2.	Calculation of the p-value among the variants
3.	Post-hoc test: Bonferroni

# Conclusion

Based on the sample size and Bonferroni-corrected p-value, the University of Montana library can choose from 3 of the 4 proposed names, as there's no significant difference in click numbers. I recommend using the names 'Connect,' 'Services,' and 'Help' based on the lowest corrected p-value for the new web page.

