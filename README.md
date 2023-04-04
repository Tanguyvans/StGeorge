# StGeorge
In this repository we will try to identify if Saint-George is on the image. Before entering into the classification, we will apply a few preprcessing steps. Afterwards, we will apply different achitecture trying to reach the highest accuracy. On the next section, we will specify the function of each file. 

## Files 
1. Managing_dataset : This files intends to gather all images into one dataset. This dataset is filled with the images from the .csv files and the kaggle online dataset. 
2. Classifier_xception : In this first solution, we finetune an Xception model to classify the dataset using tensorflow. 
3. Classifier_ViT : For the second solution, we apply a Visual Transformer. 
4. Prediction_xception : With the fine tuned xception model we can use it to make predictions. 
