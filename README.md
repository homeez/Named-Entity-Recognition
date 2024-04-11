# Named-Entity-Recognition
Named Entity Recognition Analysis Using bi-LSTM and Conditional Random Field (CRF)



## Abstract
This study explores the application of natural language processing techniques in Named Entity Recognition (NER), employing a bidirectional Long Short-Term Memory (biLSTM) neural network in conjunction with Conditional Random Fields (CRF). NER plays a pivotal role in identifying and classifying entities in unstructured text, such as people, organizations, and locations. This assessment investigates the architecture, training process, and evaluation metrics of the biLSTM-CRF model to enhance entity recognition accuracy and context-awareness in NLP systems.

## Introduction
Named Entity Recognition (NER) is a crucial task in Natural Language Processing (NLP), emphasizing the identification and classification of entities within text. This analysis focuses on the synergistic combination of biLSTM and CRF techniques, addressing the challenges in NER by capturing contextual information and sequential dependencies. The study delves into the technical intricacies, practical implications, and potential impacts of employing biLSTM and CRF for enhancing NLP applications.

## Key Components of the Analysis
1. **Techniques Employed:**
   - **biLSTM (Bidirectional Long Short-Term Memory):** A recurrent neural network (RNN) capturing contextual information from both past and future inputs.
   - **CRF (Conditional Random Fields):** A probabilistic model enhancing entity recognition accuracy in sequence labeling tasks.
2. **Evaluation Metrics:**
   - **Confusion Matrix:** Illustrates the model's performance across different entity classes.
   - **Classification Report:** Provides precision, recall, F1-score, and support for each entity class.
3. **Objectives of the Analysis:**
   - Train a biLSTM-CRF model for NER.
   - Evaluate the model's performance using evaluation metrics.
   - Analyze precision, recall, and F1-score to assess the model's effectiveness.

## Theoretical Architecture of biLSTM-CRF for Named Entity Recognition
The biLSTM-CRF architecture integrates bidirectional LSTM for contextual understanding and CRF for effective sequence labeling. This collaborative approach enhances NER accuracy by considering both local and global dependencies in the data.

## About the Dataset
The dataset features four columns:
- **Sentence:** Unique identifier for each sentence.
- **Word:** Individual words for detailed analysis.
- **POS (Part of Speech):** Categorizes words into grammatical classes.
- **Tag:** Annotations or labels, including NER labels, for each word.

## Importance
NER is essential for various NLP applications, including information extraction, question answering, and language understanding. This analysis aims to enhance the effectiveness of NER tasks by leveraging the biLSTM-CRF model architecture.
