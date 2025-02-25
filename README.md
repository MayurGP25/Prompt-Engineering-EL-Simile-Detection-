The repository contains a ipynb file which can be added to a google colaboratory environment.
Clone the repo to system and upload the ipynb file to colab
Connect to a GPU runtime in Colab by navIgating to runtime->change runtime->GPU
Install the necessary reuirements using !pip install command
The inital cells are for training of BERT + LSTM model with random weights and the .h5 model will be saved in /content in files section of colab workspace itself.
The next cell will take this weghts file to make predictions on test set (alternatively, the previous training weights file is also available in the repository)
Likewise, there is training cell of BERT + Fully Connected Layer model as well
A model weights file can be fetched from /content/bert_models in files section (Cross Validation will add 5 models to this folder)
Similarly, this model can be tested on test dataset and confusion matrix can be printed for insights.
