# StrokeData - Study Project using Google Colab

**Educational Objectives**
Exercise the following concepts of tools:
✓ Exercise the Spark MLLib module of Apache Spark.

**Description**
Heart-related diseases affect millions of people worldwide and, according to the World Health Organization (WHO), they are the second leading cause of death in the global population. As a data scientist, you have been hired to create a predictive model that, based on patient data such as age, gender, glucose level, smoking status, predicts whether that patient will have a stroke or not. The file `stroke_data.csv` contains patient attributes and a "stroke" attribute, indicating whether that patient suffered a stroke event or not.

This exercise aims to answer the following questions:

## 1. How many records are there in the file?
## 2. How many columns are there in the file? How many are numeric? When reading the file with `spark.read.csv`, enable `inferSchema=True`. Use the `printSchema()` function of the DataFrame API.
## 3. In the dataset, how many patients suffered a stroke, and how many did not?
## 4. From the dataframe, create a temporary table using `df.createOrReplaceTempView('table')` and then use `spark.sql` to write a SQL query that retrieves the number of patients who had a stroke by work type. How many patients suffered a stroke and worked, respectively, in the private sector, independently, in the government, and how many are children?
## 5. Write a `spark.sql` query to determine the proportion, by gender, of study participants. Most participants are:
## 6. Write a `spark.sql` query to determine who is more likely to have a stroke: hypertensive or non-hypertensive. You can write a query for each group. From the probabilities you obtained, do you conclude that:
## 7. Write a `spark.sql` query that determines the number of people who suffered a stroke by age. At what age did the largest number of people in the dataset suffer a stroke?
## 8. Using the DataFrame API, determine how many people suffered strokes after the age of 50.
## 9. Using `spark.sql`, determine the average glucose level for people who respectively suffered and did not suffer a stroke.
## 10. What is the average BMI (Body Mass Index) of those who suffered and did not suffer a stroke?
## 11. Create a decision tree model that predicts the chance of stroke using the continuous/categorical variables: age, BMI, hypertension, heart disease, average glucose level. Use the content from the second interactive lesson to create and evaluate the model.
## What is the accuracy of a built model?
## 12. Add to the model the categorical variables: gender and smoking status. Use the content from the interactive lesson to deal with categorical variables. Did the accuracy (quality) of the model increase to:
## 13. Add to the model the categorical variables: gender and smoking status. Use the content from the interactive lesson to deal with categorical variables. Which of these variables is more important in the decision tree model you built?
## 14. Add to the model the categorical variables: gender and smoking status. Use the content from the interactive lesson to deal with categorical variables. What is the depth of the decision tree?
## 15. How many nodes does the decision tree have?
