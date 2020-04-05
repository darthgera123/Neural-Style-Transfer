# Neural-Style-Transfer

Neural Style Transfer is basically taking the style of a painting and superimposing it on an image. This was a revolutionary idea proposed by Gatys in 2015 and the paper can be found [here](https://arxiv.org/abs/1508.06576).  

It argues that the style of the image is encoded primarily in the lower layers of vgg-19 model trained on Image net for object detection while the higher layers encode the content information.  

We take a noisy image to start with and optimize it simultaneously with the style and content image.Interestingly we dont optimize on the weights but rather on the pixel values.  

## Some results -  
<p float="left">
  <img src="https://github.com/darthgera123/Neural-Style-Transfer-/blob/master/images/pablo.jpg" width="320" height="250" />

  <img src="https://github.com/darthgera123/Neural-Style-Transfer-/blob/master/results/pablo_better_1024.png" width="320" height="250" />
</p>

<p float="left">
  <img src="https://github.com/darthgera123/Neural-Style-Transfer-/blob/master/images/the_scream.jpg" width="320" height="250" />

  <img src="https://github.com/darthgera123/Neural-Style-Transfer-/blob/master/images/scream.png" width="320" height="250" />
</p>
<p float="left">
  <img src="https://github.com/darthgera123/Neural-Style-Transfer-/blob/master/images/japan.jpeg" width="320" height="250" />

  <img src="https://github.com/darthgera123/Neural-Style-Transfer-/blob/master/results/japan_output_1024.png" width="320" height="250" />
</p>

<p float="left">
  <img src="https://github.com/darthgera123/Neural-Style-Transfer-/blob/master/images/starry_night.jpg" width="320" height="250" />

  <img src="https://github.com/darthgera123/Neural-Style-Transfer-/blob/master/results/starry_output_1024.png" width="320" height="250" />
</p>
<p float="left">
  <img src="https://github.com/darthgera123/Neural-Style-Transfer-/blob/master/images/whistler.jpg" width="320" height="250" />

  <img src="https://github.com/darthgera123/Neural-Style-Transfer-/blob/master/results/whistler_output_1024.png" width="320" height="250" />
</p>
<p float="left">
  <img src="https://github.com/darthgera123/Neural-Style-Transfer-/blob/master/images/painting.jpeg" width="320" height="250" />

  <img src="https://github.com/darthgera123/Neural-Style-Transfer-/blob/master/results/painting_output_1024.png" width="320" height="250" />
</p>

The hyperparameters would be different for every image. 

## References
+ https://towardsdatascience.com/how-to-get-beautiful-results-with-neural-style-transfer-75d0c05d6489
+ https://towardsdatascience.com/breaking-down-leon-gatys-neural-style-transfer-in-pytorch-faf9f0eb79db
+ https://nextjournal.com/gkoehler/pytorch-neural-style-transfer
