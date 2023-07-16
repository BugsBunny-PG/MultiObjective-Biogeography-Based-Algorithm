# MultiObjective-Biogeography-Based-Algorithm
# About

According to the nature of evolutionary algorithms, result is different in various runs due to its random nature.
Here, two performance measures are calculated: the number of selected features, classification accuracy.
The BBO algorithm operates based on the idea that species migrate between habitats and that the likelihood of migration is influenced by the habitat quality and similarity between habitats. In the context of 
optimization, candidate solutions in the search space are considered as habitats and the quality of a habitat is determined by its fitness value, which is also called the habitat suitability index (HSI) to evaluate its quali-ty as a solution. Since we are dealing with an optimi-zation problem, a High-HSI habitat represents a good solution and a Low-HSI habitat is a poor solution. 
The BBO algorithm consists of several key steps:
1. Initialization
2. Fitness Evaluation
3. Migration
4. Mutation
5. Elitism

# Working Strategy

By applying the BBO algorithm to the selected feature subset obtained in the previous step. This iterative process allows for the refinement of the feature subset by focusing on local search within the selected subset. By progressively optimizing the 
feature subset through iterations and creating the da-taset of selected features, and again apply BBO on 
selected features dataset with the aim of not to com-promise with accuracy from the previous run of the BBO, this process will continue until the number of features will keep reducing and accuracy would be maintained or become better.  Our goal is to identify the most 
discriminative features that significantly contribute to find Accurate result in real world Problem
