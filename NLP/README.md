# Toxic Comment Classification with Neural Networks

This project aims to classify comments based on their toxicity using neural networks. The main objective is to preprocess the data, perform text augmentation, and train models for predicting toxic comments.

## Steps for the Project:

1. **Data Exploration and Preprocessing**:
   - Investigate the dataset, clean the data, and split it into train, validation, and test sets. Models should be fine-tuned on the validation set, and test set should be used for final evaluation. 

2. **Data Augmentation**:
   - Augment the dataset by either scraping additional data or finding similar datasets (including datasets in other languages and using translation tools like Google Translate). The goal is to enhance the training dataset.

3. **Custom Data Preprocessing**:
   - Apply custom preprocessing methods such as lemmatization or stemming, and create a custom tokenizer. Ensure the data is processed correctly for model input. Implement an efficient DataLoader for handling the dataset.

4. **Transfer Learning**:
   - Download a pre-trained model with its necessary tokenizer (from sources like Hugging Face, Rusvectores, or other open repositories). Fine-tune the model for the task of toxicity classification. Optimize and tune the model for better performance.

5. **Model Evaluation and Selection**:
   - Evaluate the models trained on the validation set, and analyze the results on the test set. Choose the best-performing model based on accuracy and other relevant metrics (such as F1 score). Submit the final model in the leaderboard.

## Technologies Used:
- PyTorch
- HuggingFace Transformers (for pre-trained models)
- Tokenization (spaCy, HuggingFace tokenizer)
- Pandas (for data manipulation)
- Numpy
- Scikit-learn (for model evaluation)
