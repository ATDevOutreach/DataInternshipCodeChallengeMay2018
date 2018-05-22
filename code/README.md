**TASK 1**
* Copy Paste AI Bot.

**TASK 2**
1. Define the task. 
- Define the Problem. 
- Define deliverables. 
- Get an idea of what the Dataset is about. 

2. Explore the Data. 
- How big is the dataset? 
- Explore the various columns in the data. 
- Explore the format of the data. Is it text based such as Yes, No? Numerical data such as 1, 25.43? 
- Are there missing values? 
- Is the Data organised and systematic? For example: Is there any column data that is merged with another column? 

3. Data Cleaning 
- If given a huge dataset, How many columns, rows? 
- If given a huge dataset, print column names. 
- Remove rows that do not meet agreed criteria. For example: Empty rows or rows with majority missing values

4. Data Analysis
- Remove unnecessary columns such as Names or PersonID that are not meaningful to the data.
- Fill Missing Values through various techniques such as averaging column values. 
- Map categorical formats to Numerical formats. For example: {Male:1, Female:2}
- Find relationships between columns, i.e Correlation to understand important variables. 
- Plot graphs of distribution: For example Payments vs Company. 

5. Machine Learning
- Divide Dataset into train and test sets
- Find the most important features. 
- Choose an algorithm suited for the problem. 
- Train algorithm on dataset
- Test algorithm's accuracy, precision, among others on training set
- Improve algorithm or Implement on top of the algorithm. 

**TASK 3**
1. Classifies Data samples into k distinct groups of equal variance. For example:

Weight | Height | Male or Female? 
------ |------- | --------------- 
  70   | 7      |   Female         
  90   | 8      |   Female        
  40   | 4      |   Male          
  42   | 4.2    |   Male          

K= 3, Classify Weight: 60 and Height: 6
```
   1.  √(70-60)^2 + √(7-6)^2 = √11
   2.  √(90-60)^2 + √(8-6)^2 = √32
   3.  √(40-60)^2 + √(4-6)^2 = √22
   4.  √(42-60)^2 + √(4.2-6)^2 = √19.8
   
   K = 3, Select the 3 smallest values:
   -> √11 (Female), √22 (Male), √19.8 (Male)
   -> K Means would classify Weight (60) and Height(6) as Male.  
   This is because the variance is almost equal between Males and the unlabeled data as compared to Females and the unlabeled data.  

```

**TASK 6** 
* On the Notebook




