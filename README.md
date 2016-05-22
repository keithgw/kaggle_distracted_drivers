# kaggle_distracted_drivers
Kaggle competition to classify distracted driver behavior based on images

## Files  
1. make_train_csv.ipynb  - Creates a CSV of images and training labels
2. EDA_distracted_drivers.ipynb - Exploratory Data Analysis on Training Images, some PCA representations  
3. train_PCA.ipynb - Using 200 principal components, trains a RF and SVM model. 

### Notes :  
*train_PCA* 5/20.  Low training log loss on both RF and SVM models, with slightly higher validation log loss. However, Test submissions getting much higher log loss in the 1.9 - 2.3 range. This model is overfitting. Probably could massage the model parameters to reduce variance, and increase bias, but it is probably more likely that the PCA representation is not generalizing well.
