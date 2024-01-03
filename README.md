# Brain_tumor_detection_resnet
* Used resnet50
* MRI image dataset containing 7023 images
* 5712 images used to train the model, 655 for validating, and 656 for testing
* 4 categories(no_tumor,meningioma,pituitary,glioma)
* Image augmentation has been done to get better accuracy and image resizing has been done to reduce computational effort

# Classification_report
|class     |precision|recall|f1-score|support|
|:--------:|:-------:|:----:|:------:|:-----:|
|glioma    |0.94     |0.98  |0.96    |149    |
|meningioma|0.98     |0.88  |0.93    |148    |
|notumor   |0.99     |1.00  |0.99    |208    |
|pituitary |0.97     |1.00  |0.98    |151    |
|accuracy  |         |      |0.97    |656    |
|macro avg |0.97     |0.96  |0.96    |656    |
|weighted  |0.97     |0.97  |0.97    |656    |
avg       

#Confusion_Matrix

<img src="https://github.com/Md-Shahriar-Islam/Brain_tumor_detection_efficient_net_CNN/assets/88028870/e53ebae2-7a0a-41a8-b86b-2cf3e9ea1ea4" width="500" height="500"></br>
#loss_vs_epoch

<img src="https://github.com/Md-Shahriar-Islam/Brain_tumor_detection_efficient_net_CNN/assets/88028870/090246df-ae0c-4a17-b640-fe24bdc86dd2" width="500" height="500">
#accuracy_vs_epoch

<img src="https://github.com/Md-Shahriar-Islam/Brain_tumor_detection_efficient_net_CNN/assets/88028870/fd0cc7e9-1b9a-4a79-a9cf-806674616bfd" width="500" height="500">
