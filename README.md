# Lab 6: Market Basket Analysis

This lab focuses on identifying relationships between products purchased together using association rule mining.
We applied both Apriori and FP-Growth algorithms to discover frequent itemsets and strong association rules.

Steps performed:
1. Data loading and cleaning
2. Frequent itemset mining with Apriori
3. Association rules generation and visualization
4. Frequent itemset mining with FP-Growth
5. Performance comparison

Visualizations include:
- Top-N frequent itemsets bar plot
- Heatmap of item co-occurrences
- Lift vs Confidence scatter plot

## Purpose
The purpose of this lab was to explore **market basket analysis** using two popular algorithms — **Apriori** and **FP-Growth** — on a transactional retail dataset.  
We aimed to:
- Identify frequent itemsets purchased together.
- Derive association rules to uncover product relationships.
- Compare the performance of Apriori and FP-Growth.

## Key Insights
- Several strong associations were found (e.g., gift items and decorative products frequently appeared together).
- **Support, confidence, and lift** metrics were used to evaluate rule strength.
- FP-Growth provided the **same frequent itemsets** as Apriori but with **faster execution time**.
- Visualizations (bar plots & heatmaps) made it easier to interpret item relationships.

## Challenges & Decisions
- **Data cleaning:** Many transactions had missing descriptions or quantities ≤ 0. We removed these to ensure data quality.
- **Minimum support selection:** Experimented with multiple thresholds to balance between too few and too many itemsets.
- **Performance measurement:** Added runtime tracking to fairly compare Apriori and FP-Growth.
- **Item naming:** Decided to keep original product descriptions instead of abbreviations for better interpretability.