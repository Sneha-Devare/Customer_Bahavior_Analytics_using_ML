**Project - Customer Behavior Analytics**

Businesses increasingly rely on advanced analytics to predict customer behaviour and optimize operations. Accurately predicting whether a customer **will make a purchase** and estimating their **annual spending** allows companies to fine-tune marketing efforts, design personalized offers, and improve customer retention. However, this requires handling complex, noisy datasets, selecting the right features, and engineering new ones to capture nuanced customer behaviour.

**Objective :**

The goal is to develop a machine learning model to predict the customer **Will_Purchase** or not and customers **Annual_Spending**.

1.	A **classification model** to predict the likelihood of a customer making a purchase (Will_Purchase), using both direct and derived behavioural indicators.

2.	A **regression model** to predict the annual spending (Annual_Spending) of a customer, taking into account multiple nonlinear interactions and latent patterns.

**Dataset Overview :**

The dataset contains **50,000 entries** representing customer data, enriched with complex interactions and noise to simulate real-world scenarios.

It includes:

**Demographic features:** Age, Gender, Marital Status, Education Level.

**Behavioural features:** Purchases in the last month, Online activity level, Days since last purchase, Customer loyalty score.

**Derived features:** Age-to-income ratio, Online purchase tendency, and Income category.

**Complex interactions:**

Nonlinear relationships between features (e.g., Age vs. Income).

Latent behaviour patterns like combined loyalty and purchasing frequency.

**Target variables:**

 Will_Purchase: Binary (1 = Yes, 0 = No).

 Annual_Spending: Continuous value indicating yearly spending in dollars.

**Univariate Analysis:**

 Checking distributions, skewness, patterns, counts in features.

**Bivariate Analysis:**

 Uncovering relationships, patterns, dependancies among two or more features.

 **Class Imbalance:**

 1. Oversampling
    
 2. Undersampling



