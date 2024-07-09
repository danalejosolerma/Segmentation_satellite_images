# Segmentation of satellite images
Convolutional neural network built using Keras developed to classify different objects from RGB aerial images. The dataset used to train this convolutional neural network was obtained from Kaggle https://www.kaggle.com/datasets/humansintheloop/semantic-segmentation-of-aerial-imagery and contains 6 different classes as follows:
   1. Building: #3C1098
   2. Land (unpaved area): #8429F6
   3. Road: #6EC1E4
   4. Vegetation: #FEDD3A
   5. Water: #E2A929
   6. Unlabeled: #9B9B9B
   
  The convolutional network was coded following the tutorial from DigitalSreeni
  https://www.youtube.com/watch?v=jvZm8REF2KY&t=2058s&ab_channel=DigitalSreeni
  
Considering a batch size of 64 images and 26 epochs it was obtained during training a Jaccard similarity (SIMRATIO) of 0.7431 , which is pretty decent for the simplicity of the model. Visual inspection, show that the results obtained are a fair approximation of what is desired for this task.
