# hangman-challenge-nlp-with-bert
Transformer-based Hangman solver (PyTorch, BERT-style) predicting masked letters. Achieves >60% in 100 games and 100% in 5 games, outperforming GPT-4.1 (40% in 5 games). Includes hyperparameter search, Colab support, early stopping, and batch gameplay.


# Key Features

- **Custom BERT-like Transformer**: Built from scratch for letter-level prediction in Hangman.
- **High Performance**: Achieves >60% accuracy in 100 games, and 100% in 5-game tests—significantly outperforming GPT-4.1 (40% in 5 games).
- **Hyperparameter Search**: Automated grid/random search over model size, layers, heads, dropout, and more.
- **Batch Gameplay & Benchmarking**: Play single or multiple games, and measure model success rate.
- **Colab Ready**: Switches for Google Colab compatibility, including Drive integration for model persistence.
- **Early Stopping & Checkpointing**: Training includes early stopping, best model saving, and flexible device support (CPU/GPU).
- 

## Accuracy Benchmarks

| Model          | Games | Accuracy   |
| -------------- | ----- | ---------- |
| This BERT Model| 100   | >60%       |
| This BERT Model| 5     | 100%       |
| GPT-4.1        | 5     | 40%        |

