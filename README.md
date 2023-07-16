# MultiObjective-Biogeography-Based-Algorithm
# About

According to the nature of evolutionary algorithms, result is different in various runs due to its random nature.
Here, two performance measures are calculated: the number of selected features, classification accuracy.

# Working

By applying the BBO algorithm to the selected feature subset obtained in the previous step. This iterative process allows for the refinement of the feature subset by focusing on local search within the selected subset. By progressively optimizing the 
feature subset through iterations and creating the da-taset of selected features, and again apply BBO on 
selected features dataset with the aim of not to com-promise with accuracy from the previous run of the BBO, this process will continue until the number of features will keep reducing and accuracy would be maintained or become better.  Our goal is to identify the most 
discriminative features that significantly contribute to find Accurate result in real world Problem
