# Emotion-detection
CNN based emotion detection using FER2013 dataset in Kaggle -check whether there are 7 folders for each classes (happy, neutral, sad, angry, fear, disgust and surprise).
##  Notice  ##

**Website for emotion dtetction dataset (FER2013):
https://www.kaggle.com/datasets/msambare/fer2013?resource=download

**Packages need to be installed (for jupyer notbook usage)
- pip install opencv-python
- pip install numpy
- pip install matplotlib
- pip install deepface
- pip install keras
- pip3 install --upgrade tensorflow
- pip install pillow
- pip install shutil
- pip install scipy

**Instructions:

step-1: Download the dataset (fer2013) using the website provided above.
-check whether there are 7 folders for each classes (happy, neutral,sad,angry,fear,disgust and suprise).

Step-2:run the train file (Training.ipynb); .ipynb is becuase of I used jupyter notebook.
-NB: if you are using Google colab, to upload the dataset and any required folders, first you must compress the folder and upload to the colab dirctory. Then extract the uploaded file (.rar) using the code provided (eg: for dataset.rar): 
!unrar x "/content/dataset.rar" "/content"

-NB: if you are using jupyter notebook, spyder or pycharm environements, first you must download the required libraries for all project by using,"Download_libraries.ipynb". But if you are using Colab just already setted so you can pass the library downloading part.  

Step-3:After setting-up all the intial condition stated and upload the files (for colab: use the google driev address provided) all the intial condition stated, run the first code in the "Testing.ipynb" code.
- The files to be uploaded in the colab environement are:
1. The dataset (upload when using training.ipynb) 
2. The smaple videos (upload when using tesing.ipynb) 
3. haarcascades(upload when using tesing.ipynb) 


**NB: to get the path of any file on Google-colab: just right click on the required file listed to the left and click on "copy path". 


** For Google-colab:
-select the runtime to GPU under: Runtime>Change runtime type before uploading any file.
-upload the above three files
-start running by importing the trianing file
-Skip the step-2 if you wish to use pre-procced dataset if not use first the extracting code the run step-2 by focusing/changing the dirctory in the code.
-Agian find the directory and replace the path for step-3 
- Also change the directory under step-6 (Train the model) part
- Then good to good to go to step-4

Step-4: Run the code under step-7 & 8 to place the saved model (emotion_model.h5 & emotion_model.json) at the final step into the best_model folder. 

Step-5:For testing the trained model use; "Testing.ipynb" file.
-Google-colab: open using colab and select the runtime type to GPU.Then upload the trainde model, "best_model".
-To upload the model, first compress the best_model folder.Then upload the best_model.rar file to colab.
-Also upload the "haarcascade" folder to the colab.
-if you wish to test using videos, upload the video to the colab first and use step-6 by replacing the directory to the dirctory you want to feed.

**if you wish to use smart phone camera as webcome (for fine resolution), use "Iriun webcam".
-Install this Ipcam on your labtop and smart-phone.
-Open it at both devices(labtop & phone).
-connect both devices to the same wifi-network.


**For dataset i used google-drive and uploaded at google-drive and the address is: https://drive.google.com/file/d/16hVWGBCw9gfJz_PQvGwWYt7mSr6g6-y_/view?usp=sharing 


Links:
-For training google-colab:
1) 50 epochs GPU trained:https://colab.research.google.com/drive/1mY0CKGlm6rx-d5sJ6mdszWOoYDRWjJy2?usp=sharing
 2) 100 epochs GPU
https://colab.research.google.com/drive/1wy5xQa0u3b4isjwld-ZeIj-ymoTlqoig#scrollTo=7f2ef76b

-For testing google-colab
https://colab.research.google.com/drive/15sPGL5aVrbI3xar7SFxrVPTebAP9w4QW#scrollTo=debc3d77

