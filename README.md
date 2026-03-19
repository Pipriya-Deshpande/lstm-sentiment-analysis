# lstm-sentiment-analysis
Sentiment analysis project using LSTM, lexicon embedding, and Flask.

## Overview
This project implements a sentiment analysis model using a two-level LSTM architecture combined with lexicon embedding and polar flipping techniques to improve classification accuracy.

## Problem Statement
Traditional sentiment analysis models assume clean and accurately labeled datasets. However, real-world text data often contains complex sentiment structures and noisy labels, making classification challenging.

## Approach
The project proposes:
- Two-level LSTM network for hierarchical feature learning
- Lexicon embedding to incorporate linguistic sentiment cues
- Polar flipping mechanism to handle contextual sentiment changes

  ## Workflow
1. Data collection and preprocessing
2. Text cleaning and tokenization
3. Sequence padding
4. LSTM-based model training
5. Sentiment prediction
6. Web interface using Flask

## Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Flask

## Features
- Deep learning-based sentiment classification
- Handling complex sentiment structures
- Integration with web interface for user input

  ## Project Structure
- `sentiment_analysis.ipynb` – model training and preprocessing
- `app.py` – Flask application
- `images/` – UI screenshots
- `docs/` – original project documentation

## Future Improvements
- Improve model performance with hyperparameter tuning
- Use pretrained embeddings (Word2Vec, GloVe)
- Deploy using cloud services (AWS)
