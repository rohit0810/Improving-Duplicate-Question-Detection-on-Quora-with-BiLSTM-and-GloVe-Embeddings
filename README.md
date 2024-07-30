# Improving-Duplicate-Question-Detection-on-Quora-with-BiLSTM-and-GloVe-Embeddings
Objective: Developed a machine learning model to identify duplicate questions on Quora, utilizing Bi-directional Long Short Term Memory (BiLSTM) networks for efficient text sequence analysis. This project aimed to enhance the user experience by minimizing redundant content on the platform.

Model Architecture: The model incorporated an embedding layer with pre-trained GloVe vectors, followed by BiLSTM layers to capture contextual information from both questions. Additional features included common word length metrics and dense layers for further refinement. The model was trained with a combination of early stopping, model checkpointing, and learning rate reduction techniques.

Performance Metrics: Achieved an overall F1-score of 0.83, with precision and recall values of 0.88 and 0.84 for class 0, and 0.75 and 0.81 for class 1, respectively. The model demonstrated strong generalization with balanced performance across both classes, making it effective for detecting duplicate questions on Quora.

The dataset for this project can be found here: https://www.kaggle.com/c/quora-question-pairs
