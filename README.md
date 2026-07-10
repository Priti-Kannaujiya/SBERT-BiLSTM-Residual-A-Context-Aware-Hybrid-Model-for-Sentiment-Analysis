# SBERT-BiLSTM-Residual-A-Context-Aware-Hybrid-Model-for-Sentiment-Analysis
This repository presents a proposed SBERT-BiLSTM Residual architecture for multi-class sentiment classification. The framework uses SBERT for contextual feature extraction, BiLSTM for learning sequence-level dependencies, and a residual connection to preserve important features and improve representation flow.

Input comments are tokenized using SBERT and passed through the SBERT encoder to generate contextual embeddings. These embeddings are processed by a BiLSTM layer, followed by mean pooling to create a fixed-size feature vector. The pooled vector is then refined through a fully connected layer with ReLU activation, dropout, and a residual connection before final sentiment classification.

The proposed model predicts one of three sentiment classes:

- `0`: Positive
- `1`: Negative
- `2`: Neutral
 #                                            ARCHITECTURE
<img width="1473" height="671" alt="WhatsApp Image 2026-05-14 at 2 34 25 PM" src="https://github.com/user-attachments/assets/6d7b1cba-5946-44fc-80e7-e6ddee32c206" />
