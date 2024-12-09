# Sentiment Analysis of US Airlines: An NLP Approach

---

## Project Summary

This project investigates customer sentiment about six major US airlines by analyzing Twitter data using advanced Natural Language Processing (NLP) models. By categorizing tweets as **Positive**, **Neutral**, or **Negative**, the study helps airlines improve customer satisfaction, brand loyalty, and operational decision-making.

---

## Key Highlights

### Dataset
- Source: **Twitter US Airline Sentiment Dataset** (Kaggle).
- Over 14,000 labeled tweets.
- Sentiment Classes: Positive, Neutral, Negative.
- Metadata: Airline names and timestamps.

### Models
- **BERT** (Bidirectional Encoder Representations from Transformers):
  - Achieved 80.87% accuracy and an F1-score of 80.54%.
  - Outperformed RoBERTa in all evaluation metrics.
- **RoBERTa** (Robustly Optimized BERT):
  - Reached 73.29% accuracy and an F1-score of 71.62%.

### Preprocessing Steps
1. Tokenization of tweets.
2. Noise removal (e.g., URLs, hashtags).
3. Retention of emojis and mentions for sentiment markers.

### Evaluation Metrics
- **Accuracy**: Percentage of correct predictions.
- **Precision**: Measure of exactness.
- **Recall**: Measure of completeness.
- **F1-Score**: Harmonic mean of precision and recall.

---

## Challenges Addressed

1. **Noisy Data**: Removal of typos, hashtags, and redundant spaces.
2. **Short Text Length**: Capturing sentiment in 280-character tweets.
3. **Contextual Complexity**: Handling sarcasm, slang, and mixed emotions.
4. **Computational Intensity**: Fine-tuning large transformer models.

---

## Results

| Model      | Accuracy | Precision | Recall | F1-Score |
|------------|----------|-----------|--------|----------|
| **BERT**   | 80.87%   | 80.36%    | 80.87% | 80.54%   |
| **RoBERTa**| 73.29%   | 71.33%    | 73.29% | 71.62%   |

**Sentiment Analysis Observations:**
- **Negative tweets** dominate, highlighting common customer grievances.
- **Neutral tweets** mostly contain factual or indifferent content.
- **Positive tweets** are fewer, reflecting moments of customer satisfaction.

---

## Key Insights for Airlines

1. **Enhance Customer Service**:
   - Address complaints about delays, cancellations, and poor service.
2. **Strengthen Brand Loyalty**:
   - Focus on positive experiences to encourage favorable feedback.
3. **Data-Driven Strategies**:
   - Utilize actionable insights to refine operations and services.

---

## Future Work

- Mitigate class imbalance with data augmentation.
- Experiment with advanced NLP architectures.
- Integrate multimodal data (e.g., images, videos) for deeper analysis.

---

## How to Run

1. Clone the repository.
3. Preprocess data and fine-tune BERT and RoBERTa models.
4. Evaluate results using test data.
5. Visualize outcomes using provided Jupyter notebooks.

---

## Thank You

---

