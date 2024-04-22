# CSE508_Winter2024_A4_2020408
 
# Jupyter Notebook: Fine-Tuning GPT-2 for Text Review Summarization

This notebook guides through fine-tuning Hugging Face's GPT-2 model on Amazon Fine Food Reviews dataset for summarization.

## Author: 
ShrugalTayal (shrugal20408@iiitd.ac.in)

## Data Preparation
- Clean and preprocess 'Text' and 'Summary' columns.

## Model Training
1. **Initialize GPT-2 Tokenizer and Model**
2. **Data Splitting**: 75:25 for training and testing.
3. **Custom Dataset Class** for data prep.
4. **Fine-Tune GPT-2** on review dataset.
5. **Hyperparameter Tuning** for optimization.

## Evaluation
- Compute ROUGE scores on test set to assess model performance.
- Examples with ROUGE scores for comparison.