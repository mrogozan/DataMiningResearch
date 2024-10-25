# Subgroup Discovery on Time-Series Data: Exploring the Impact of Overlapping Slices
**2AMM20 - Exceptional Model Mining Track - Group 30**

This is the GitHub repository containing the code, data and results of the investigations conducted by group 30 of 2AMM20, TU/e, 2024-25.

- Folder **overlapped data slices** contains the input to the subgroup discovery task, i.e.: datasets for the four different overlap configurations
- Folder **results** contains the output data of the subgroup discovery algorithm, and lists for each overlap configuration the subgroups and their details.
- File **dataset_generation_feature_extraction.ipynb** is the notebook which implements the synthetic data generation, slicing and the feature extraction
- File **random_gen_dataset_with_patterns.csv** is the raw synthetically generated data, without slicing and feature extraction
- File **result_evaluation.ipynb** finds indexes of slices with injected patterns and evaluates the quality of the subgroups discovery task results by counting the number of correct slices detected
- File **subgroup_discovery.ipynb** implements the subgroup discovery task via GP-Growth, by using the *pysubgoup* module

