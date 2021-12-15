# Neural Network Model 



# Overview
Hey! Looks like you want to use NN to train/predict. If you're looking to train the model from scratch or make updates use the training python notebook. If you want to simply use the models use predict python notebook. 

------------------------------------------

# Data

Right now upload it will work on the format which we uploaded. You can make changes to the dataset. 

------------------------------------------

# Trainging from scratch. 

To train fromscartch you would need to mount the notebook on drive.

- Simply run the first cell, a pop up will come up
- allow colab to make changes in the drive
- a id will get generated, simply copy it and paste it in the dialog box in google colab.

Why did we need to mount it on drive? Well the program is saving the model. So you won't need to train again to access it

After mounting it on drive, 
- create a folder in google drive, upload the training and testing files.
- update the *DATA_DIR* in the second cell to your folder path 
- eg * `DATA_DIR = '/content/drive/MyDrive/'your_path'`
- Now you're all set to train the model

Your models will get saved in the data_dir you just made.

------------------------------------------

# Using pre-trained model

If are looking to use the pretrained model, simply download the 2 models and use this [drive link](https://drive.google.com/drive/folders/106KPVoYnHHfnh0ulC1D00xislzHxf1aK?usp=sharing) to get the model for nitrogen. After extracting it paste it in the models folder.
Like in the previous step, upload the model in a folder and change the data_dir. 


Your pre-trained models should have a DATA_DIR as 
- `/content/drive/MyDrive/'your_path'/Models/Carbon`
- `/content/drive/MyDrive/'your_path'/Models/Benzene`
- `/content/drive/MyDrive/'your_path'/Models/Nitrogen`

Now you can simply run all the cells
