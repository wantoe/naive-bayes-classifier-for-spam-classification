# Naive Bayes Classifier for spam classification
A Naive Bayes classifier to implement spam classification on messages. 
The classifier classifies if an email is a spam or ham. An email is represented using a binary bag-of-words model. Specifically, a message is represented as a set of  𝑘  keywords, that is,  𝑚𝑒𝑠𝑠𝑎𝑔𝑒=(𝑤1,...,𝑤𝑘) , where  𝑤𝑖=1  if the keyword  𝑤𝑖  appears in the message and  𝑤𝑖=0  otherwise. 
The classifier is trained using 1000 sample emails. It's accuracy is then determined after testing it with 500 test emails. The accuracy is 0.838 .

# How to use?
You can read the code in "ai5_naive_bayes" in github 
Or
1) Installing Python and Jupyter using the conda package manager. The miniconda distribution includes a minimal Python and conda installation.
2) Use the Jupyter application to open the file "ai5_naive_bayes". Click the "Cell" tab and then Run all the cells 

The ipynb file contains all the information regarding the assignment.

# What I learnt?
- implementation of Naive Bayes classifier and Laplace-smoothing, a technique of supervised machine learning. 
