[//]: # (Image References)

[image1]: ./images/sample_dog_output.png "Sample Output"
[image2]: ./images/vgg16_model.png "VGG-16 Model Keras Layers"
[image3]: ./images/vgg16_model_draw.png "VGG16 Model Figure"


## Convolutional Neural Networks (CNN) project 

 Given an image of a dog, the algorithm will identify an estimate of the canine’s breed.  If supplied an image of a human, the code will identify the resembling dog breed.  

![Sample Output][image1]


### Dataset

1. Location `dog-project/dogImages` populated from the [dog dataset] at (https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip) 

2. Location `/dog-project/lfw` populated with images from the [human dataset] at (https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip).  

3. Pre-trained models use features from [VGG-16 bottleneck features](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogVGG16Data.npz) for the dog dataset.  located at location `path/to/dog-project/bottleneck_features`.

4. Code in the jupyter notebook.
`
dog_app.ipynb
`
