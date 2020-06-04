# CNNSimple
Provides simple toy datasets to test on common deep neural network (DNN) architectures and perform layerwise relevance propagation using [iNNvestigate](https://github.com/albermax/innvestigate) using the provided example notebooks. Notebooks also explore the impact of adding informative variables until the network has an AUC of the ROC of 1.0, and a loss of ~1 (exhausting the phase space of the network).

File | Purpose
------------ | -------------
makeJetImages.ipynb | Makes toy "jet" images (based on [Jet-Images -- Deep Learning Edition](https://arxiv.org/abs/1511.05190).
fourvec_data.ipynb | Makes toy "four vector" data in the format (pt, eta, phi, mass).
CNN_2D.ipynb | 2D model that classifies the images as "signal" or "background" is defined and trained.
LRP_CNN2D.ipynb | Takes 2D CNN and jet images as input and creates heat maps of the relevant input features.
CNN_1D.ipynb | 2D model that classifies the toy vectors as "signal" or "background" is defined and trained.
MLP_multin.ipynb | Feed-forward dense network with only the variables used to make the jet images, and not the images themselves as inputs.
deprecated | Holds older versions of CNN's and data making scripts.
