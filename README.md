# NLP-Classification
Recognising whether the tweets on X(Twitter) are disaster related.
Disaster Tweet Classification
This project aims to classify tweets as either relating to real disasters or not using Natural Language Processing (NLP) techniques and machine learning.

## Dataset
The project uses the "Natural Language Processing with Disaster Tweets" dataset, which includes:

train.csv: Training set (7613 samples)
test.csv: Test set (3263 samples)

## Dependencies
numpy

pandas

tensorflow

keras_core

keras_nlp

scikit-learn

seaborn

matplotlib

## Setup
Clone the repository
Install the required dependencies:

## Data Preprocessing
Text length analysis
Train-test split (80% train, 20% validation)
Tokenization using DistilBERT tokenizer

## Model
The project uses a DistilBERT-based classifier:
DistilBERT backbone
Dense layer for pooling
Dropout for regularization
Output dense layer for classification

## Training
Batch size: 32
Epochs: 4
Optimizer: Adam with learning rate 1e-5
Loss function: Sparse Categorical Crossentropy

## Evaluation
Accuracy and loss metrics
Confusion matrix visualization
F1 score calculation

## Usage
Run the Jupyter notebook Disaster_Tweets_Code.ipynb to train the model and evaluate its performance.

## Future Work
Experiment with different model architectures
Implement cross-validation
Try other NLP techniques like data augmentation or ensemble methods
