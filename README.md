# Text Summarization
### Maximizing Productivity while Reducing Reading time

This project focuses on text summarization using two different models, LSTM and T5, on the CNN/Daily Mail dataset. Text summarization is a process of creating a concise and coherent summary of a large document while retaining the key information and overall meaning.

## Dataset

The dataset used in this project is the CNN/Daily Mail dataset, which consists of news articles along with their corresponding summaries.

## Models

The LSTM (Long Short-Term Memory) and T5 (Transformer) models were selected for this project. LSTM is a type of recurrent neural network that is well-suited for text summarization. T5 is a transformer-based neural network model that has been shown to be very effective for text summarization.

## Evaluation

The quality of the summaries generated by the LSTM and T5 models were evaluated using the ROUGE (Recall-Oriented Understudy for Gisting Evaluation) score. For the LSTM model, we achieved a ROUGE-1 score of 0.7118, while for the T5 model, we achieved a ROUGE-1 score of 0.826087.

## Future Work

Future work could include exploring the use of other models and techniques such as hierarchical summarization, incorporating external knowledge sources, and utilizing multimedia sources such as images, audio, and video to aid in text summarization. In addition, other evaluation metrics such as BLEU, METEOR, and CIDEr could be explored to evaluate the quality of the generated summaries.

## Requirements

Python 3.x
TensorFlow
Transformers
NLTK
Pandas
Numpy
