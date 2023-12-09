# CSCI-567-BIRD-VOCALIZATION-CLASSIFICATION-USING-SUPERVISED-CONTRASTIVE-LEARNING
Birds, vital indicators of environmental health, require accurate identification through calls for effective monitoring. Our study enhances this using supervised contrastive learning with deep CNN architectures on mel-spectrograms. Objective: improve training convergence.

Procedure to train the model:
1. Download the dataset of melSpectrograms from the given link:
2. Upload this dataset to kaggle and unzip it.
3. Use phase-1 training.ipynb notebook to train using supervised contrastive learning.
4. Save the weights as "sk_with_contrastive_loss.pth". The saved weights can be accessed from the given link:
   https://drive.google.com/file/d/1DZUYaBrwW6NRXvQgsqb2IPQRDwQX6g6z/view?usp=sharing  
5. Upload "sk_with_contrastive_loss.pth" inside a folder named "model-weights" to phase-2 training.ipynb notebook to train the model using supervised learning. After training the model, we get an CMAP score of 82.58%. 
6. Save the weights from this model as "skresnet18_with_contrastive loss.pth". The saved weights can be accessed from the given link:
    https://drive.google.com/file/d/1R3jSCWQYMPenFuwVFmF7xlja6MOOfdCG/view?usp=sharing

Procedure to test the model on the test data:
1. Use the saved weights from this link: and upload it to kaggle in a folder named ____________
2. Use testing-phase.ipynb 
