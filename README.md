# Coursera-IBM_Data_Engineering_Machine_Learning_with_Apache_Spark

This lab is not bug ridden, just excessively long and tedious, like wading through diarrhea trying to learn despite an instructor nots so concerned with helping students learn (opinion)

All the steps are listed in the attached juytor source file "final project"

The answers to the final test are as follows:

Part 1 – ETL Questions
Q1. How many rows are present in the dataset (NASA_airfoil_noise_raw.csv)?

Answer: From the df.count() output, the total number of rows in the raw dataset is:
1522 rows.

Q2. How many rows are present in the dataset after the duplicate rows are dropped?

Answer: After removing duplicates with df.dropDuplicates(), the row count is:
1503 rows.

Q3. How many rows are present in the dataset after the duplicate rows and rows with null values are dropped?

Answer: After dropping null values with df.dropna(), the row count is:
1499 rows.

Q4. What is the new column name of the old column SoundLevel?

Answer: The old column SoundLevel was renamed to:
SoundLevelDecibels.

Q5. What is the name of the parquet file that was created after dropping duplicates and null row removal?

Answer: The parquet file created is named:
NASA_airfoil_noise_cleaned.parquet.

Q6. How many rows are present in the cleaned parquet dataset?

Answer: After reading the cleaned Parquet file, the row count is:
1499 rows.

Part 2 – Machine Learning Pipeline
Q7. What is the first stage of the machine learning pipeline?

Answer: The first stage of the pipeline is:
VectorAssembler.

Q8. What is the second stage of the machine learning pipeline?

Answer: The second stage of the pipeline is:
StandardScaler.

Q9. What is the third stage of the machine learning pipeline?

Answer: The third stage of the pipeline is:
LinearRegression.

Q10. What is the name of the column mentioned as labelCol in the LinearRegression stage of the pipeline?

Answer: The label column in the LinearRegression stage is:
SoundLevelDecibels.

Part 3 – Model Evaluation
Q11. What is the value of the metric Mean Squared Error (MSE)?

Answer: The MSE is:
22.59.

Q12. What is the value of the metric Mean Absolute Error (MAE)?

Answer: The MAE is:
3.73.

Q13. What is the value of the metric R Squared (R²)?

Answer: The R² score is:
0.54.

Q14. What is the value of the intercept?

Answer: The intercept is:
125.14.

Part 4 – Persist the Model
Q15. How many stages are there in the pipeline model?

Answer: There are 3 stages in the pipeline.

Q16. What is the coefficient for Frequency?

Answer: The coefficient for Frequency is:
-3.9728.

Q17. What is the coefficient for AngleOfAttack?

Answer: The coefficient for AngleOfAttack is:
-2.4775.

Q18. What is the coefficient for ChordLength?

Answer: The coefficient for ChordLength is:
-3.3818.

Q19. What is the coefficient for FreeStreamVelocity?

Answer: The coefficient for FreeStreamVelocity is:
1.5789.

Q20. What is the coefficient for SuctionSideDisplacement?

Answer: The coefficient for SuctionSideDisplacement is:
-1.6465.

