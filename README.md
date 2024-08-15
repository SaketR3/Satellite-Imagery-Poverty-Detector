<h1 align="center">Satellite Imagery Poverty Detector</h1>



<h4 align="center">Premise</h4>
In developing nations, it can be difficult to determine where impoverished areas are, as techniques such as conducting surveys are expensive. Yet, knowing where areas of poverty are is critical for determining which regions humanitarian efforts should be directed to first, and more. 
<br />
<br />
That's where deep learning comes in. ML engineers have trained neural networks in the past that analyze satellite imagery and determine how much wealth the regions in the images have, based on features such as housing, light levels, and more. These neural networks can tell from the images which regions are more likely to be in poverty. 
<br />
<br />
This project is my take on this deep learning application. 
<br />
<br />



<h4 align="center">Data</h4>
After searching through various datasets, I decided to train my model on the WILDS PovertyMap dataset, which consists of a large amount of 224 x 224 satellite images.
<br />
<br />


<h4 align="center">Model Architecture and Training</h4>
I created a convolutional neural network (CNN) with several convolutional and pooling layers followed by a few dense (fully-connected) layers at the end. The model also included a few batch normalization and drop-out layers. 
<br />
<br />
As for training, I trained the model using a custom training loop, and was able to achieve an RMSE of 0.34. 
<br />
<br />



<h4 align="center">Tech Stack</h4>
I used TensorFlow's Keras API for defining the model, and I used TensorFlow's lower-level API for model training

