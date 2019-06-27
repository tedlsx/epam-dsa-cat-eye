# epam-coca-cola-project
## Find model
### Classification

First, we need to calculate the probability of buying each drinks for each householderID. The probability can be calculated by 
<img src="http://www.sciweavers.org/tex2img.php?eq=p_%7Bbuy%7D%20%3D%20n_%7Bbuy%7D%2Fn_%7Ball%7D&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0" align="center" border="0" alt="p_{buy} = n_{buy}/n_{all}" width="132" height="21" />

Then try use the result of 10-fold cross-validation of each classification machine learning algorithms: the majority classifier (Maj), the naive Bayesian classifier
(NB), K-Nearest Neighbor (kNN), Support Vector Machines (SVM) and Random forest (RF). Where the majority classifier can be treat as base model, use the sensitivity (true positive rate or recall) to verify the goodness of model.


-- <cite>"Modelling In-Store Consumer Behaviour Using
Machine Learning and Digital Signage Audience
Measurement" by Robert Ravnik, Franc Solina, Vesna Zabkar</cite><https://core.ac.uk/download/pdf/151478114.pdf>

#### Naive-Bayes Classification
##### GaussianNB
Prior distribution is Gaussian distribution and most features have continues data type
##### MultinomialNB 
Prior distribution is Multinomial distribution and most features have category data type
##### BernoulliNB
Prior distribution is Bernoulli distribution and most features have binomial categories data type or sparse discrete value