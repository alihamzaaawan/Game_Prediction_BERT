# Game_Prediction_BERT

NOTE: Model was Trained on FinalBert.ipynb and learner on learner1.ipynb

For Testing the model, follow the instructions below




1) Download the file 'LoadModel.ipynb' from this repo.

2) Open the file in google colab ( https://colab.research.google.com/?utm_source=scs-index )

3) Download the model files 'tf_model.h5' and 'tf_model.preproc' from the google link below.
Model folder link: https://drive.google.com/drive/folders/1rflKh7s9vz39MTFiyBU_D3wyfS_jVILq?usp=sharing

4) You can upload the model files to your Google drive new folder named 'PublicBERTmodel', mount your Google drive in your Colab project (3rd button below **'Files'**) and copy the path of that folder from the project file directory and paste it in place of PATH  **predictor = ktrain.load_predictor('PATH')**
**The above method is more reliable.** 
The path would look like this ''/content/drive/MyDrive/PublicBERTmodel''

OR

4) Create a new folder named 'model' inside your project and Upload the files 'tf_model.h5' and 'tf_model.preproc' to the new folder created 'model' in your project. Make sure the upload is complete, it will appear before completing in '/content/model/' path. (for loading we need to give the path of the folder and not just the .h5 file). After upload completion, run the code.



<img width="341" alt="Screen Shot 2021-12-05 at 4 29 51 PM" src="https://user-images.githubusercontent.com/62678861/145143200-2efb6658-832e-430b-8f9f-d62465bf454a.png">


