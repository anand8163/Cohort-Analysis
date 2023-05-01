# Cohort-Analysis
Performs Cohort Analysis on a given dataset using Jupyter notebook which includes libraries like pandas,matplotlib and seaborn to get details about a retail store and see which products is being sold repeatedly and which are not

# Objective:-

# After understanding and working with this notebook,you will be able to do:

•Understand what is cohort and cohort analysis.

•importing libraries. 

•Handling missing values.

•Month extraction from date.

•Calculate number of unique customers in each group.

•Create cohort table for retention rate.

•Visualize the cohort table using heatmap.



Let's start-

# What is Cohort and Cohort Analysis?

A cohort is simply a group of people with shared characteristics.

Cohort analysis is a type of behavioral analytics in which you take a group of users, 

and analyze their usage patterns based on their shared traits to better track and understand their actions.

•First of all imported multiple libraries which include:-

Pandas

matplotlib

Seaborn
![Screenshot (18)](https://user-images.githubusercontent.com/125815238/235438539-8f9c5aa1-6919-4eae-a60c-1cb4d83b96f9.png)

•To read the file in jupyter notebook we have to first call it in jupyter 

and then show the header and information of the file
![Screenshot (19)](https://user-images.githubusercontent.com/125815238/235438860-e94eb9c8-bcd5-4b0f-b07c-221dc04cc090.png)

3.Created a column index with the first time customer which include cohort months
![Screenshot (20)](https://user-images.githubusercontent.com/125815238/235445578-5a641881-c96c-4d8c-b505-a271fda9a32d.png)

•By counting the number of customerID using cohort month and cohort index

we can see the results for cohort month and cohort index.

one more thing here shows that how the customerID is unque in every detail

so that we can get only unique data and not duplicate/null data.
![Screenshot (21)](https://user-images.githubusercontent.com/125815238/235446622-29305adb-cdf5-4115-a985-a49c3964d57e.png)

•Now as you have looked into the data that how data has been called into different sections,

so now creating cohort table and seeing values 
![Screenshot (25)](https://user-images.githubusercontent.com/125815238/235447900-237540ac-5897-4a11-a997-f55222ae7a0a.png)

•And now to visualize the cohort using heatmap we have called different colour functions,

to see how heatmap looks.

![Screenshot (24)](https://user-images.githubusercontent.com/125815238/235448092-690aca8c-4be5-4ae0-8355-afd0308936eb.png)

•As we have seen above to get the correct view of heatmap with

percentage and the functions,numbers in proper order

and to look in sorted order. 

The final cohort heatmap looks like this and in this we can see

how in every month with repect to cohort index changes 

![Screenshot (26)](https://user-images.githubusercontent.com/125815238/235448613-09a50378-b876-4379-a51d-d522bacc41a6.png)
