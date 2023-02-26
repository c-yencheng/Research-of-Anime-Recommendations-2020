# Research-of-Anime-Recommendations-2020

This report studies the factors that affect anime scores and builds a prediction model for anime scores based on the dataset "Anime Recommendation 2020" using linear regression. The big data tools include PySpark, MapReduce, Hive, and Impala. All the code used and the final model can be found in the appendix. This report first briefly introduces the background and overall content of the study. Next, the problem statement introduces the problem identification process and proposes this paper's main research questions. Chapter 3 introduces the information of the dataset selected for this report and explains why Big Data and this dataset are used for research. The next chapter introduces the methodology of this report, which mainly includes the following four parts: 1. Preliminary screening of factors by screening the correlation between columns and scores of different datasets; 2. Processing datasets, removing NA values, and converting data 3. Build the model; 4. Display the results and model accuracy. Finally, in Chapter 5, we summarize the obtained models and factors. The limitations of the research project are critically analyzed to give practical recommendations.

## Anime LRegression.ipynb
- Using PySpark to run linear regression.

## mapreduce.ipynb
- Using MapReduce technique to cleanse genre column, since there could be one or more types of genre in one value.
