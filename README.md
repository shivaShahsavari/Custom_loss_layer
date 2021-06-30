# Custom_loss & Custom_layer

## 1) Custom loss function in Siamese network  
In this repository, I implemented Siamese Network with custom loss function "contrastive_loss".  
By running 'SiameseNetwork_customLoss.py' code, you can see the structure of model like below:  
<p align="center">
<img src="image/model_layers.png" height=500 width=350>  
</p>

and the whole model as below which takes two image inputs and check the dissimilarity of the pair :  
<p align="center">
<img src="image/Siamese.png" height=300 width=600>  
</p>  

After finishing the training part, droping of loss on training set and evaluation set is: 
<p align="center">
<img src="image/Loss.png" height=300 width=500>  
</p>

Ten random samples of paired data with their dissimilarity values seem like below image. More closer to 0 means more similarity. Those pairs with more than 0.5 value are colored red.  
<p align="center">
<img src="image/display_image.png" height=400 width=900>
</p>

## 2) Custom layer  
