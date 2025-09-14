# Frequent Itemset Mining from Scratch

This project is a **from-scratch implementation of frequent itemset mining** on the Groceries dataset.  
It demonstrates two classic algorithms commonly used in market basket analysis:

## Algorithms

- **PCY Algorithm (Park–Chen–Yu):**  
  Uses hashing and bitmaps to efficiently reduce the number of candidate pairs while scanning transactions.  
  This method is memory-efficient and highlights how hashing can speed up the discovery of frequent item pairs.

- **Apriori-style Algorithm:**  
  A direct approach that counts items, pairs, and triplets by iterating over baskets and pruning based on minimum support.  
  While simpler to understand, it requires more memory and computation compared to PCY.

## Dataset

- **Groceries dataset** (~39,000 supermarket transactions).  
- Transactions are grouped by customer ID (`Member_number`).  
- Items are listed under `itemDescription`.  

## Features

- Frequent item discovery based on support thresholds.  
- Frequent pair and triplet identification.  
- Association rule generation with **support, confidence, and lift**.  
- Comparison between the hash-based PCY algorithm and the counting-based Apriori approach.  


