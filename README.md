# Skinskan
# $10,000 Grand Prize Winner - School of AI Global HealthHack
Sacramento Health AI Hackathon Project - Consumer Skin Cancer Recognition App

By Rithwik Sudharsan, Edison Li, Alex Fung, Mario Ishhe, and Huzaifa Ahmad

The model architecture is given in Keras .json format. The model weights are given in Keras .h5 format.

Code for the model training can be found in the .ipynb. 

We used the following for the model:
- 28x28 RGB image training data mostly for faster training time and less variation in imaging.
- Standard LeNet CNN 
- 4 Outputs: Melanoma (Malignant/Benign) and Keratosis (Malignant/Benign). 

These were chosen for purposes as outlined by this landmark Stanford research project, https://cs.stanford.edu/people/esteva/nature/. 

--> Keratosis is the most common type of skin lesion, and Melanoma is the most deadly type of skin lesion. Thus, these are the two most important to classify for information on identifying the lesion. 

The Stanford research paper had 55.4 ±  1.7% CNN accuracy (trained with Inception v3) and is meant for clinical use, trained on the dataset we used by also tens of thousands of Stanford Hospital data and other paid academic data for a total of ~130,000 training images. They cited that "two dermatologists attain 65.56% and 66.0% accuracy on a subset of the validation set." 

All the training data is from dermatoscope imaging. Thus, our project is meant for non-clinical use but for individuals who notice a lesion and would like a quick yet accurate diagnosis via dermatoscope attachment to smartphone either for personal use or for one-time use at local pharmacies such as a CVS. While the model can run on normal close-up smartphone images, lighting will be nonideal and the image may be blurry, providing less accurate results. There are other applications in smartphone app stores that focus on this more layman imaging.


AI HACKATHON ZIP has the iOS app

https://docs.google.com/presentation/d/1vaxYNNezJ4kET6rhOa_EaCtWjaPx0T2rLQLay8Eoavs/edit?usp=sharing - Google Slides Presentation - THIS COMMIT WAS ONLY FOR THE PRESENTATION (that's why it is after the deadline, asked for permission from organizers)
