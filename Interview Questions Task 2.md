1. What’s the point of EDA?
EDA is like getting to know your data before doing anything serious with it.
 You’re basically exploring—looking for patterns, spotting weird values, checking what’s missing, and figuring out what’s useful. 
 It helps you make smarter decisions before jumping into building models.

2. How do boxplots help?
Boxplots are great for quick insights. 
They show you the spread of your data and help you spot outliers easily. 
Like, if one passenger paid $500 for a Titanic ticket and most others paid under $100, a boxplot will make that jump out immediately.

3. What’s correlation, and why should I care?
Correlation tells you how two variables move together. 
If two features are tightly linked—like fare and passenger class—it’s helpful to know. 
It can tell you what’s important, and also help you avoid including redundant info in your models.

4. How do you know if your data is skewed?
You can usually see it in a histogram—if the graph leans heavily to one side, it’s skewed. Like if most people paid low fares but a few paid crazy high ones, that’s right-skewed. You can also check it mathematically with a skewness score.

5. What’s multicollinearity?
That’s when two or more features are kind of saying the same thing. For example, if you had both “house size in sq ft” and “house size in sq meters,” they’d be nearly identical. This can confuse your model, especially linear ones, and mess up the interpretation.

6. What tools do you use for EDA?
I mostly use Python with libraries like pandas, seaborn, and matplotlib. If I want to get fancy or automate reports, I’ll use sweetviz or pandas-profiling. For dashboards or presentations, sometimes I’ll bring in Tableau or Power BI.

7. Ever had EDA save the day?
Totally! One time, I noticed a bunch of customers in a churn dataset had a “tenure” of 0 months. 
It turned out they hadn’t even activated their accounts yet—just created them. 
That insight helped clean the data and boosted our model’s performance a lot.

8. Why is visualization so important in ML?
Visuals make things click. 
They help you see the story your data is telling.
 Whether it’s spotting outliers, checking if a model is biased, or explaining results to someone non-technical—visuals turn complex info into something clear and actionable.