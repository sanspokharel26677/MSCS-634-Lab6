
# Lab 6: Frequent Itemset Mining with Apriori and FP-Growth

## Overview
This lab explores frequent itemset mining using two popular algorithms:
1. **Apriori**
2. **FP-Growth**

We implement both algorithms, compare their performance, and analyze the results.

## Steps Completed

### 1. Data Preparation
- Loaded and preprocessed the dataset.
- Converted transactional data into a one-hot encoded format suitable for mining.

### 2. Apriori Algorithm
- Applied the Apriori algorithm with `min_support = 0.01`.
- Measured execution time.
- Extracted frequent itemsets.

### 3. FP-Growth Algorithm
- Applied the FP-Growth algorithm with `min_support = 0.01`.
- Measured execution time.
- Extracted frequent itemsets.

### 4. Performance Comparison
- Created a comparison table including:
  - Algorithm Name
  - Minimum Support
  - Execution Time (seconds)
  - Itemsets Found
- Added a bar chart for visual comparison of execution times.

**Example Table:**
| Algorithm   | Min Support | Execution Time (seconds) | Itemsets Found |
|-------------|-------------|--------------------------|----------------|
| Apriori     | 0.01        | 7.19                     | 1853           |
| FP-Growth   | 0.01        | 24.35                    | 1853           |

### 5. Association Rules
- Generated rules from frequent itemsets.
- Calculated metrics: support, confidence, and lift.

### 6. Analysis & Interpretation
- Embedded markdown explanations after outputs.
- Discussed why Apriori was faster in this dataset compared to FP-Growth.

### 7. Enhancements
- Added execution time benchmarking.
- Added visualization for performance comparison.
- Structured notebook with clear markdown explanations.

## Results Summary
- **Apriori** outperformed **FP-Growth** in execution time for this dataset.
- Both algorithms returned the same number of frequent itemsets.
- Performance differences are dataset-dependent.

## Files in Submission
- `lab6_frequent_itemset_mining.ipynb` - Jupyter Notebook with full implementation.
- `README.md` - This file summarizing the lab work.

---
**Author:** Sandesh Pokharel  
**Course:** Advanced Big Data and Data Mining  
