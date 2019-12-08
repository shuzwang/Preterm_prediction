# Preterm_prediction

## Dependencies

You will need some standard packages in R, such as `tidyr`, `dplyr`, `scipy` and `ggplot2`. To run the SVM function, you need to have R packages `e1071` and `dismo`

## How to Run

### SVM Model

The SVM function is wrapped in `SVM_model.R` script. You need to specify the feature genes you selected, training data, kernel function, gamma hyperparamter for kernel, 
the proportion of validation set, and seed. It will return the svm model, prediction accuracy vector, and a average prediction accuracy across validation.

## Development

Main development steps are all included in the R script 
Including:  
- Find top 100 differentially expressed genes
- Develpment of SVM model
- Select hyperparamters
