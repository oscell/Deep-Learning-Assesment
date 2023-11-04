# Deep-Learning-Assesment


In this assessment the task was to use two Convolutional Neural Networks (ConvNets) to identify different types of cell nuclei in cancer samples. 

The main goal is to aid pathologists in diagnosing colon cancer by digitally identifying cell types from microscope images of colon biopsies, using machine learning to classify the nuclei of cells into one of four types:

- normal
- cancer
- muscle
- immune cells.

The data consists of a training set with labeled 100x100 pixel images of cell nuclei and a test set with unlabeled images. I developed and trained two models: 

- A custom small ConvNet with eight layers.
- A pre-trained torchvision model adapted to this task through transfer learning. 

Both models underwent hyperparameter optimization and produced loss and  accuracy curves, as well as confusion matrices to diagnose classification issues. The models were also interpreted using Captum to understand their decision-making processes.
