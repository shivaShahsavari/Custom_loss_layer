# Custom_loss & Custom_layer

## Custome loss function  
In this repository, I implemented Siamese Network with custom loss function "contrastive_loss".  
By running 'SiameseNetwork_customLoss.py' code, you can see the structure of model like below:  
<img src="image/model_layers.png" height=500 width=350>  

and the whole model as below:  
<img src="image/Siamese.png" height=300 width=600>  

After finishing the training part, the progress of loos on training set and evaluation set is:  
<img src="image/Loss.png" height=300 width=500>  


Ten random samples of paired data with their dissimilarity value seems like below image. More closer to 0 means more similarity. Those pairs with more than 0.5 value are colored red.  
<img src="image/display_image.png" height=400 width=900>
