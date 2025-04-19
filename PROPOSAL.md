
Project Proposal: Sentiment Analysis on IMDB Reviews with BERT

Dataset
The dataset for this modeling experiment is the IMDB Large Movie Review Dataset, available via the Hugging Face `datasets` library.

It contains 50,000 movie reviews labeled as either positive or negative sentiment, evenly balanced.

Modeling Approach
The goal of this project is to explore fine-tuning a pre-trained transformer model specifically BERT for binary sentiment classification.  

My workflow will include:
- Loading and preprocessing the dataset using `datasets`
- Tokenizing using `BertTokenizer` from Hugging Face Transformers
- Training a `BertForSequenceClassification` model using the `Trainer` API
- Evaluating model performance (accuracy, F1 score, and confusion matrix)
- Comparing with a TF-IDF + Logistic Regression baseline

The final notebook will be organized with comments, visuals, and explanations to make the process clear for other students.

The full project will be developed in a Jupyter notebook format within this repository.
