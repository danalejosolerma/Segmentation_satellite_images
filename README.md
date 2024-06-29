# Segmentation of satellite images
Convolutional neural network built using Keras developed to classify different objects from RGB aerial images
The dataset used to train this convolutional neural network was obtained from Kaggle
https://www.kaggle.com/datasets/humansintheloop/semantic-segmentation-of-aerial-imagery
that contains 6 different classes as follows:
   1. Building: #3C1098
   2. Land (unpaved area): #8429F6
   3. Road: #6EC1E4
   4. Vegetation: #FEDD3A
   5. Water: #E2A929
   6. Unlabeled: #9B9B9B
   
  The convolutional network was coded following the tutorial from DigitalSreeni
  https://www.youtube.com/watch?v=jvZm8REF2KY&t=2058s&ab_channel=DigitalSreeni
  
  The results obtained are a first good approximation of what is wanted for this task.
  The trained network can be used by downloading the file 'u_net_semantic.h5'. During the training it was obtained a Jaccard similarity (SIMRATIO) of 0.7925, which is pretty decent for the simplicity of the model.
