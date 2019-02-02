# Dog-Breed-Classification---CNN
Udacity Project - A Deep Learning Classifier to identify dog breeds
This work was done as part of the requirements for the Udacity Nanodegree. The training data is too big to be uploaded here, hence only the final IPython notebook is uploaded. Since this is a project with the template provided from Udacity, I'll list down the major points I implemented myself

1) Created a CNN classifier from scratch in Pytorch, to classify dog breeds into 133 different categories. The architecture was decided after reading much about best practices in creating CNN classifiers, and of course experimentation.The model achieved > 10 % accurcay.
2) Created a second classifer, this time employing transfer learning. This implied tweaking a pretrained Inception based architecture, which achieved a far higher accuracy of 77%
3) Some work was also done in the area of using face detection in images using opencv 
