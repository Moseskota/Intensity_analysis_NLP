# Intensity_analysis_NLP

This project explores different machine learning models to classify the intensity of emotions (Angriness, Happiness, Sadness) expressed in textual data. The dataset consists of labeled text samples manually annotated with one of these three emotions.

**Models Explored**:

**Support Vector Machine** (SVM): Achieved good performance with an average F1-score of 0.768.

**Random Forest**: Showed competitive performance with an average F1-score of 0.757.

**XGBoost**: Outperformed SVM and Random Forest with an average F1-score of 0.781.

**Naive Bayes**: Performed adequately with an average F1-score of 0.717.

**BERT Fine-Tuning**:
BERT (Bidirectional Encoder Representations from Transformers) was fine-tuned for this emotion classification task. Due to the smaller dataset size, overfitting was observed despite regularization efforts. The BERT model achieved an average F1-score of 0.794 after hyperparameter tuning.

**Conclusion**

For larger datasets, BERT fine-tuning shows promising results, especially with appropriate regularization techniques. However, based on this study's findings with a smaller dataset, XGBoost emerges as a robust alternative for emotion intensity classification in text.
