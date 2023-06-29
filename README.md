# Titanic Kaggle challenge 

Notebook for the Titanic challenge on Kaggle : https://www.kaggle.com/competitions/titanic

The main steps of the notebook are as follows:
  - Compute correlation to see what would be the relevant features
  - Test 3 different architectures:
      - Random forest classifier (RFC)
      - Support vector classifier
      - Neural network
  - For each architecture :
      - Calculation of accuracy on a validation set
      - Selection of hyperparameters by plotting validation curves
      - Plot learning curve to evaluate bias and variance
- For the RFC, error analysis to identify whether any particular features stand out in the misclassified cases, in order to identify ways of improving.
  - Selection of the architecture giving the best accuracy: RFM
  - Training on the entire trainingset
