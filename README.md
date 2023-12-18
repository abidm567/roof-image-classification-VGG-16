# roof-image-classification-VGG-16
This model utilises VGG-16 trained on imagenet for classification of Roof images dataset containing 255 images belonging to 3 classes - Ashphalt roofs, Tile roofs and Metal roofs
Saved models were uploaded inorder to save time training the models again.
The code uses two approached - 
1) Without finetuning and using the pretrained model on our dataset
2)With finetuning by unfreezing the last 2 layers to train
ImageDataGenerator from keras was used for image pre-processing and resizing the image before feeding into VGG-16 model
Observations:
Model with finetuning performed significantly better than pretrained model achieving 85% test accuracy compared 57% accuracy without finetuning.
