**Movie Genre Association Rules**
Recommendation System Using Market Basket Analysis (Apriori)

This project applies Market Basket Analysis using Association Rule Mining to uncover meaningful relationships among movie genres.
**Project Objective**

The main objectives of this project are:

Preprocess movie genres into a machine-learning-ready format

Apply One-Hot Encoding to convert genre combinations into transactions

Use the Apriori algorithm to find frequent genre sets

Extract association rules (support, confidence, lift)

Identify strong genre combinations that help build better recommendations

**Data Preprocessing**

1. Splitting Genres
2. One-Hot Encoding
3.The Apriori algorithm was used to identify frequent genre combinations.
4.Generating Association Rules

**Metrics used:**
| Metric         | Meaning                                               |
| -------------- | ----------------------------------------------------- |
| **Support**    | Frequency of itemset in dataset                       |
| **Confidence** | Probability of B given A                              |
| **Lift**       | Strength of the association compared to random chance |

**Technologies Used**

Python

Pandas

mlxtend (Apriori, Association Rules)

One-Hot Encoding (str.get_dummies)

Jupyter Notebook
