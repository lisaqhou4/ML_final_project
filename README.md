# ML_final_project

#Final_Project_Final_Version.ipynb:
The preprocessing, training, and evaluating code are all contained in Final_Project_Final_Version.ipynb. The manually labeled data that we used to train the model is in the data_1106_labeled folder. This notebook first sets up the pretrain model, define training and evaluation function. Then it imports and preprocess the data. The model is then fine-tuned using the tokenized and clean datasets.  The comparison and evaluation between Fine-tuned & Pre-trained model, non Fine-tuned & Pre-trained model, and non Fine-tuned & non Pre-trained model are also performed in this notebook. 


#TCM_Prediction.ipynb:
To make prediction on tweets, run the TCM_Prediction.ipynb which imported our optimal model [fine_tune_model_dict_shuffle_llr_gen_entire.bin ](https://drive.google.com/file/d/1--7Va7et8ep0IF-FrHn2kxvrZ8I60dtu/view?usp=sharing) (too large to upload to git repository.) TCM_Prediction.ipynb preprocess the raw tweets, add tokens, and then make predictions on the tweets and also produce visualization.

#Sentimental_Anlysis_Data_Preprocessing.ipynb:
This notebook only preprocess and tokenize the tweets for training. The Final_Project_Final_Version.ipynb contains the same code that this notebook has. Sentimental_Anlysis_Data_Preprocessing.ipynb was used to produce the graph and data example that were used in our final presentation.
