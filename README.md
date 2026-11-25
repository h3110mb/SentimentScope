# SentimentScope

Transformer-based binary sentiment analysis on IMDB movie reviews.

## Project Structure
```
SentimentScope/
├── SentimentScope.ipynb      # Complete notebook with all code
├── best_sentiment_model.pt   # Trained model checkpoint (~75% accuracy)
└── requirements.txt          # Python dependencies
```

## How to Use
1. Install dependencies: `pip install -r requirements.txt`
2. Open and run `SentimentScope.ipynb` in Jupyter
3. The notebook loads the checkpoint and evaluates the model

## Results
- Test accuracy: ~75% on held-out subset
- Full fine-tuning of the same architecture exceeds 90%

## References
This project was written specifically for the SentimentScope assignment. Public resources used:

- Hugging Face Transformers: https://github.com/huggingface/transformers
- Hugging Face Datasets: https://github.com/huggingface/datasets
- BERT paper (Devlin et al., 2018): https://arxiv.org/abs/1810.04805
- DistilBERT paper (Sanh et al., 2019): https://arxiv.org/abs/1910.01108
- IMDB Dataset (Maas et al., 2011)
- PyTorch: https://pytorch.org/

No code was copied from external repositories or tutorials. See the References section in the notebook for full details.