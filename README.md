# Affordability

This repository contains a machine learning guide to assess loan affordability based on borrower characteristics and repayment history. 
We do not provide preprocessing code or features'name explanation because it is part of FIOLA secret sauce. Nevertheless, if you are a referee of our papers, academic researcher or wish to co-operate at a professional level with FINEXOS and wish more context or information please send an email to the Chief Data Scientist at georgioskiminos@finexos.io and we will try to provide what you need.

Repository Contents:
1. 3 datasets, train, test and validation
2. The model to reproduce the results.

File Contents: 
1. Affordability_Model.ipynb - Main notebook for training & evaluation
2. test_data - Test dataset (features & labels)
3. train_data - Training dataset (features & labels)
4. valid_data - Validation dataset (features & labels)
5. paystring_masked_uids.parquet - Raw input data (masked UIDs)
6. README.md 

Usage:


These files allow users to validate affordability model performance using the 3 datasets provided


You can:
1. Load X_test and y_test to evaluate your own trained model
2. Use the provided model parameters for benchmarking or replication
