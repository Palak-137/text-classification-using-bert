## Text-Classification 📝
#### Text classification is one of the most crucial classifications as it involves various parameters in the consideration. I have tried to use the most accurate model BERT, which is a deep learning model which helps us to classify the words in their context, in this way the classwise distinguishment will be easier.

#### before directly feeding data to the model we have to perform a series of steps to clean and process the data. 
1. Data – Cleaning and Pre-processing:
 Text Cleaning – 
	conversion to lowercase ,
	removing punctuations and 
	characters ( using ‘re’ library ).
 Removing Stop Words – 
	used NLTK English ‘stopword’ corpus to detect stop words in a statement.
 Applying Lemmatization – 
	used NLTK wordnet and WordNetLemmatizer. 

2. Data – Augmentation: Applied Word Level Augmentation based on contextual word embeddings – Used NLP-AUG library and BERT to achieve the same. Made 4 embeddings for each statement.

## Steps to run the project:
1. The code can be run on any jupyter Notebook or Google Colab ( preferable use Google colab with GPU as hardware accelerator ).
2. Run each cell individually 


## This project is created with:
Python 3.6/3.8
libraries:  BERT, TensorFlow, Hugging Face transformers, scikit-learn, pandas, numpy, seaborn, pyLDAvis, NLTK, MatPlotLib, NLPAug, JSON .

#### Made with ❤