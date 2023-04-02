# Frequent-Itemset-Mining

The respository shows the lab about Frequent Itemset Mining that i experienced during study career at the university. In general, this lab is required to find out all popular sets in the dataset by application to Apriori without supported library (skearn, mlxtend, ...).

# General parts

- Read and explore the datasets

- Basic conception about frequent itemset mining
  - Itemset_Cover
  - Absolute_Support
  - Relative_Support
  - Frequent_itemset

- Frequent itemset mining problem
  - Basic method
  - Apriori algorithm

# Apriori algorithm
- Initialize 1-itemset
- Find $C_{k+1}$ from $L_k$ itemset
- Prune step
- Complete algorithm by looping
