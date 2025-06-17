# Affordability

This repository contains a machine learning pipeline to assess loan affordability based on borrower characteristics and repayment history. 

Repository Contents:
1. 3 datasets train, test and validation
2. The entire before preprocessing
3. The model to reproduce the results

File Contents: 
1. Affordability_Model.ipynb - Main notebook for training & evaluation
2. test_data - Test dataset (features & labels)
3. train_data - Training dataset (features & labels)
4. valid_data - Validation dataset (features & labels)
5. paystring_masked_uids.parquet - Raw input data (masked UIDs)
6. README.md - This file

Usage:
<br><br> 
These files allow users to validate affordability model performance using the 3 datasets provided
<br><br>
You can:
1. Load X_test and y_test to evaluate your own trained model
2. Use the provided model parameters for benchmarking or replication
