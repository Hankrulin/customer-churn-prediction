# Week 1 Summary

In Week 1, I set up the customer churn prediction project and prepared the working environment. 
I practiced Python, NumPy, and Pandas to strengthen my basic data analysis skills. 
I loaded the telco churn dataset, explored its structure, and identified important columns such as `Churn`, `tenure`, `MonthlyCharges`, and `TotalCharges`. To understand the columns, I write down the meaning of each column. This also help me clear understand the relationship between each column value. 


I also cleaned the dataset by handling blank values in `TotalCharges`, converting it into a numeric column, and removing rows with missing values. 
On the other hand, some of the function just check the specific type of massage. For instance, we use the `isnull()` function to check the value is 0, but it could not check the massage value is object type of blank. So we need to double check when we clean the data.

After that, I performed initial exploratory data analysis using visualizations such as countplots, histograms, and boxplots.

Through this process, I learned how to better understand a dataset before building models. 
I also found that some features, such as contract type and tenure, may be related to customer churn.

---

## Key Learnings

1. Data cleaning is important because incorrect data types and blank values can affect analysis.
2. Exploratory data analysis helps identify useful patterns before modeling.
3. Features such as tenure and contract type may play an important role in customer churn.