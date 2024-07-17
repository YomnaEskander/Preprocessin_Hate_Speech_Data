# Hate Speech Classification 

We have used several NLP techniques to load, clean and preprocess the kaggle dataset https://www.kaggle.com/datasets/usharengaraju/dynamically-generated-hate-speech-dataset for a text classification task, where a BERT model is trained on the preprocessed dataset to classify text as hate or no hate.  

Our project is Hate speech classification where we try different models (we utilized a fine_tuned LSTM as a baseline, Bert and Roberta) but the process was long
and different experiments were done to fine-tune and get the best results from bert and compare the results between the three different models then in the final
colab/notebook, we used the best fine tuned bert to classify a text as hate or no hate.

Check the notebook called FINAL_Bert.ipynb for the best fine tuned BERT and at the end of the notebook is a classification made by the model. 

Check the notebook 4LSTMNewData.ipynb for the best LSTM model with the best accuracies. 

Rest of the notebooks are experiments. 
