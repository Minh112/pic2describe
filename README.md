# Create a brief description for a picture
### Methods
This project provides solutions for briefly describing image content based on several methods. Their common point is to put images through CNN to get features with size (256,), specifically in this project I was trying to use VGG16 and InceptionV3, and use GRU-layer to process descriptions. 3 methods was developed with their main characteristics:

>- _Method-1: Add CNN-features with the output of GRU-layer to find the relationship between photo and description_
>- _Method-2: Use CNN-features as initial state-H of GRU-layer. By that way, the relationship between image and description was established_
>- _Method-3: Add CNN-features with the output of GRU-layer like method-1, but training GRU-layer with teaching-no-forced._

### Download dataset Flickr8k
You can download dataset Flickr8k in here: 
>_https://academictorrents.com/details/9dea07ba660a722ae1008c4c8afdd303b6f6e53b_
