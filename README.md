# Insurance-Project


## NTH Insurance Cracks Down on Fraud with Machine Learning
### The Challenge:
NTH Insurance, a leading provider, faces a significant threat: fraudulent claims. These deceptive acts not only cost the company millions but also inflate premiums for honest customers. To combat this challenge, NTH turned to the power of machine learning.
### Enter Machine Learning:
Our team developed a fraud detection system using ANN. These algorithms mimic a series of yes-or-no questions to ultimately classify data points. In this case, the data points are insurance claims, with the goal of classifying them as legitimate or fraudulent.
### Training the Model:
We fed the model historical claim data, including details like policyholder information, claim amount, type of damage, and past claim history. Each data point was labeled as either legitimate or fraudulent based on previous investigations. The Artificial Neural Network algorithm learned from this labeled data, identifying patterns and relationships between features that differentiate fraudulent claims.
### The Benefits of Detection:
Using a ANN for fraud detection offers numerous benefits:
#### 1. Reduced Losses: 
Accurate identification of fraudulent claims translates to significant cost savings for NTH.
#### 2. Improved Efficiency: 
The model automates the initial screening process, flagging suspicious claims for further investigation. This frees up adjusters' time for complex cases.
#### 3. Fairer Premiums: 
By mitigating fraudulent claims, NTH can potentially lower premiums for honest customers, leading to increased satisfaction and loyalty.
#### 4. Enhanced Risk Management: 
Insights gained from the model can help NTH identify areas with higher fraud prevalence, allowing for targeted risk mitigation strategies.
### Looking Ahead: Refining the Model
While the initial ANN model proved effective, we achieved a 94,4% accuracy in detection with the validation set and a further 94% with the unseen test set, which indicates slit overfitting. Although impressive at first glance, the higher rate of the validation set suggests the model might be memorizing specific patterns in the training data rather than learning generalizable insights. As a result, it might struggle to identify fraud in unseen data.
