# PokeDex
## ABOUT
This was just a fun project which classifies different images of pokemons into 10 categories. The image data used contained images of 10 different pokemons.
AlexNet was used for training purpose. The model performed quite well on training as well as test set, considering that the classes present in the dataset were not
balanced and no data augmentation was used in this project. The test set had 187 images of different pokemons, and as the test dataset was small, first the images were
visually confirmed to get an idea about how well the model is performing, and then after manualling calculating, the accuracy obtained on test set was around 88 %.
The training accuracy for this project using AlexNet model was 93%. Transfer Learning was used and many different experiments were performed for observing the effect
of learning the parameters versus using pre-trained parameters. Due to limitation of hardware,(NO GPU) , it was observed that learning many parameters would require
a lot of computational time. Therefore, even after 40 epochs, trying to learn the Feed-Forward Network or Classifier layer of AlexNet, only 60% training accuracy
was obtained. Therefore, the best results came when using pretrained parameters, and just learning the weights for the last layer. If anyone wishes to perform the 
experiment and hence requires data which I used, send a mail at: akansh.gupta1298@gmail.com . Could not upload the dataset here due to github limit.
