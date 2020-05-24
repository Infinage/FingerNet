## Siamese Network model to recognize finger prints

Not able to unlock mobile phones while your hands are sweaty can be a real annoyance. Further 
fingerprint sensors that are typically employed donot do a good job when the finger prints are 
dirty or smudged. The project aims to overcome this limitation. I've trained a *SIAMESE Network* 
on the socofing fingerprint dataset from kaggle and the model has showed some decent results on 
unseen fingerprints despite the images being artificially tampered to mimic the real world scenarios 
where the images can't be obtained all polished and neat.

Further the biggest advantage with siamese networks is that once they have been trained they can be 
used to compare on any new set of images with surprising accuracy, hence the name *One shot learning.*

Dataset Used: https://www.kaggle.com/ruizgara/socofing

The model took around 10 hours to train on GPU's. The trained model can be directly used to verify for 
matches among pairs of images. 

For further instructions on how the model was trained and the data extracted, check out the two
jupyter notebooks from the repo. The model is stored in the *saved model* format of keras.

Trained Model Link: https://drive.google.com/drive/folders/1TOeeW65XYBGaLeqMdPLpEDy9LEh1AbCE?usp=sharing

