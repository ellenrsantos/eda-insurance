# 📊 Exploratory Data Analysis - Medical Cost Personal Datasets.

![image](https://github.com/user-attachments/assets/9a974bba-4fff-49b4-9654-e6e4bcddd596)


# 📜 Context:

Health spending in the U.S. increased by 4.1% in 2022 to $4.5 trillion or $13,493 per capita. This growth rate is comparable to pre-pandemic rates (4.1% in 2019). Although government spending to manage the pandemic led to substantial increases in NHE, these expenditures significantly declined in 2021 while utilization of medical goods and services rebounded. By 2022, top-level patterns in health spending more closely reached that of the pre-pandemic period.

Overall, health spending was 17.3% of GDP in 2022, similar to pre-pandemic shares (17.5% in 2019) after an uptick in 2020 (19.5%) and 2021 (18.2%).

Personal medical cost analysis examines the costs of healthcare for individuals and populations. Factors that affect personal medical costs include: 
- Region: Per capita spending varies by region;
- Race and ethnicity: Health spending varies by race and ethnicity;
- Age: Health spending varies by age;
- Insurance coverage: Health spending varies by insurance coverage;
- Prescription drugs: Prescription drugs are a major component of healthcare costs;
- Out-of-pocket spending: Out-of-pocket spending has increased in recent years;
- Disease prevalence: Disease prevalence affects healthcare costs;
- Government actions: Government actions, such as the Inflation Reduction Act, affect healthcare costs.

Many people are familiar with the high and rising cost of health care in the United States from seeing how much they spend on their own health insurance premiums and out-of-pocket costs. In addition to these obvious health costs, there are also tax dollars that go to fund public programs and the amounts employers spend toward their employees’ health insurance premiums. Total national health expenditures include spending by both public programs and private health plans, as well as out-of-pocket health spending. Total health expenditures represent the amount spent on health care (such as doctor visits, hospital stays, and prescription drugs) and related activities (such as insurer overhead and profits, health research and infrastructure, and public health).

![total-national-health-expenditures-us-1970-2022](https://github.com/user-attachments/assets/c27219e4-2e61-4897-a31b-d242cd8ab66a)

# 📖 Description:

For this analysis, I chose a open acess dataset available in Kaggle (link below) about the cost of treatment of different patients. The cost of treatment depends on many factors: diagnosis, type of clinic, city of residence, age and so on.

Acess link: https://www.kaggle.com/datasets/mirichoi0218/insurance/code?datasetId=13720&sortBy=voteCount

📓 If you want to see more graphics and the exploratory analysis, jupyter notebook is available. 


# 💡 Insights:
i) The distribution of cost values is not symmetrical; it is positively skewed. This means that the mean of the values is greater than the median, and the mode is lower than the mean and the median.

![image](https://github.com/user-attachments/assets/401afd47-c67e-4630-9290-ed4b7396359e)

ii) This visualization highlights the significant impact of smoking on medical costs, as smokers are more likely to experience higher and more variable healthcare expenses.

![image](https://github.com/user-attachments/assets/c30a87a1-e614-4ab9-89db-49b68c590d0c)

iii) Both males and females have similar cost distributions, with most policyholders having relatively low costs and a few individuals experiencing high medical expenses.

![image](https://github.com/user-attachments/assets/a5ce2182-2f2b-4e26-9f37-ab0964075a2d)

iv) This visualization helps in understanding whether geographical location affects medical costs, showing that while distribution is similar, some regions may have more high-cost cases than others.

![image](https://github.com/user-attachments/assets/6deb8974-c3ed-435c-be5b-5f681655e03a)

v) The BMI distribution is similar for males and females, with most individuals concentrated in the overweight to obese range (25-35 BMI). The violin plot effectively shows both the density and spread of BMI values, highlighting slight differences between genders.

![image](https://github.com/user-attachments/assets/0997ec76-7f0f-4cf4-b56b-a847ff9ee4c9)

vi) While there is a slight trend indicating that individuals with higher BMI may have higher medical costs, the weak correlation (R² = 0.04) suggests that BMI is not a strong factor in predicting charges alone. Other factors likely contribute more significantly to variations in medical costs.

![image](https://github.com/user-attachments/assets/2f10a929-54cf-45a6-889a-5828df0862a6)

vii) The number of children does not appear to have a strong influence on medical charges. There is significant variability in charges across all groups, with some individuals having very high expenses in each category.

![image](https://github.com/user-attachments/assets/42415c8c-6cdb-4c01-b954-10e245952e0e)

# 📌 References:
1 - https://www.kaggle.com/datasets/mirichoi0218/insurance
2 - https://www.cdc.gov/nchs/hus/topics/health-care-expenditures.htm
3 - https://www.kff.org/health-policy-101-health-care-costs-and-affordability/?entry=table-of-contents-how-has-u-s-health-care-spending-changed-over-time
