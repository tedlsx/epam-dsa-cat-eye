# epam-coca-cola-project
## Find model
### Classification

First, we need to calculate the probability of buying each drinks for each householderID. The probability can be calculated by 
$$ 
p_{buy}=n_{buy}/n_{all}
$$

Then try use the result of 10-fold cross-validation of each classification machine learning algorithms: the majority classifier (Maj), the naive Bayesian classifier
(NB), K-Nearest Neighbor (kNN), Support Vector Machines (SVM) and Random forest (RF). Where the majority classifier can be treat as base model, use the sensitivity (true positive rate or recall) to verify the goodness of model.


-- <cite>"Modelling In-Store Consumer Behaviour Using
Machine Learning and Digital Signage Audience
Measurement" by Robert Ravnik, Franc Solina, Vesna Zabkar</cite><https://core.ac.uk/download/pdf/151478114.pdf>