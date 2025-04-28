# Bank Branch Clustering using K-Means

This project focuses on clustering bank branches based on their transactional activities using **K-Means Clustering**.  
The goal is to group branches with similar transaction patterns, helping banks make informed decisions about strategy, marketing, and resource allocation.

## 📊 Problem Statement

Cluster bank branches based on:

- Demand Drafts (DD)
- Withdrawals
- Deposits
- Branch Area (in sqft)
- Average Daily Walk-ins

## 🛠️ Techniques Used

- **K-Means Clustering**

## 🧰 Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 📈 Project Workflow

1. **Import Libraries**  
   - Imported libraries for data manipulation, visualization, and modeling.

2. **Read Data**  
   - Loaded the bank branch dataset with 1000 samples.

3. **Data Analysis and Preparation**  
   - Performed basic data cleaning and exploration.
   - Scaled the features for better clustering results.

4. **K-Means Clustering**  
   - Applied the K-Means algorithm.
   - Determined the optimal number of clusters using the **Elbow Method**.
   - Visualized the resulting clusters.

5. **Conclusion and Interpretation**  
   - Analyzed the cluster profiles to understand different types of branches.

## 📋 Conclusion

By using K-Means clustering, branches were grouped based on transactional and operational similarities.  
This clustering can support better business insights, operational planning, and marketing strategies.

## 📋 Recommendations

1.The banks in Cluster 3 have high OD and Withdrawals, but less Deposit. So, it needs to improve in making the customers Deposit more. Relatively large number of customers are visiting these banks. So, can promote various deposit schemes to these customers.

2.Customers in Cluster 3 seems to prefer payment through OD as these banks record the highest OD rate. Banks can check if OD is being made to other banks or to the same bank, and can look to create DD schemes for their own bank, so that customers will open their account with these banks and use the DD payment scheme.   

3.Customers preferring DD payment can go to banks either in Cluster 3 (if they need large space which can manage large crowd probably with more infrastructure facilities), or Cluster 0 (if they want small space where probably quick transaction can happen due to less crowd holding capacity).   

4.Size of the bank doesn't matter in accommodating large group of customers inside the bank, as Cluster 0 though having the least Branch Area, has the highest daily walk-ins. So, banks don't need to invest more in occupying large land space. This could mean Customers are visiting throughout the day rather than a large group of customers visiting during a period.   

5.Cluster 2 has large area and the proportion of withdrawals and deposits is almost equal. Most of these customers could be having a savings account since the withdrawals as well as DD are less when compared to other clusters. Customers visiting these banks are also lesser than other clusters. These banks can look at bringing in more customers and increasing the bank deposit by introducing various deposit schemes.   

6.Deposit is again less, while the withdrawals are much higher for Cluster 1. These banks can also look at introducing new deposit schemes.

7.Banks in cluster 0 and 1 need to focus on their infrastructure and banking facilities, since the area is lesser than cluster 3 and 4, whereas daily walk-ins is the highest. These banks can also look for opportunities to cross-sell products to the customers.   

