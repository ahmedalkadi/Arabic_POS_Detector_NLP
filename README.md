# Arabic POS Detector

## Instruction for POS Tagging with Arabic Dataset

### Dataset
The dataset provided is named **"Arabic POS.conllu"**. It contains labeled data for Arabic text with Part-of-Speech (POS) tags in CoNLL-U format.

### Objective
The objective of this project is to perform Part-of-Speech (POS) tagging on Arabic text using Recurrent Neural Networks (RNNs). Specifically, the Universal POS (UPOS) tags, a standardized set of POS tags that aims to cover all languages, will be used for tagging.

### Instructions

1. **Data Preprocessing:**
   - Load the provided dataset "Arabic POS.conllu".
   - Preprocess the data as necessary, including tokenization.

2. **Model Building:**
   - Design an architecture suitable for POS tagging. It is recommended to use recurrent layers such as LSTM (Long Short-Term Memory) or GRU (Gated Recurrent Unit).
   - Define the input and output layers of the model. The input layer should accept sequences of tokens, and the output layer should produce the predicted UPOS tags for each token.

3. **Training:**
   - Train the model using the preprocessed dataset.

### Project Highlights
- The POS tagging for Arabic data was carried out using LSTM with bidirectional layers, providing a significant advantage during training.
- An enhancement was implemented by increasing the maximum number of words entering the model, improving the model's performance.








