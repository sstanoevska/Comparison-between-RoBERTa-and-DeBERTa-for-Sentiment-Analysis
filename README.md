The main objective was to map multiple emotion categories into three sentiment classes: positive, negative, and neutral, and to evaluate the performance of modern transformer architectures in sentiment classification.


The project includes the following steps:

  1. Train-validation-test split with stratification.
  2. Data augmentation using random word deletion.
  3. Class balancing through oversampling.
  4. Label encoding for model compatibility.
  5. Tokenization using Hugging Face tokenizers.
  6. Fine-tuning of: RoBERTa-base & DeBERTa-v3-base
  7. Use of weighted cross-entropy loss to address class imbalance.
  8. Model evaluation using:
     -Accuracy
     -Macro F1-score
     -Precision, Recall
     -Confusion Matrix
     -Per-class metric visualization
