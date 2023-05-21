# cs6910_assignment-3

Wandb Report Link : [https://wandb.ai/cs22m024/dl_assignement_3/reports/CS6910-Assignment-3-CS22M024--Vmlldzo0NDA5ODQ4](https://wandb.ai/cs22m024/dl_assignement_3/reports/CS6910-Assignment-3-CS22M024--Vmlldzo0NDA5ODQ4)

For this assignment, I have drawn inspiration from various sources, including:

1. Aladdin Pearson's YouTube playlist on Seq2Seq Model, which can be accessed at: [YouTube playlist on Seq2Seq Model](https://www.youtube.com/watch?v=EoGUlvhRYpk&list=PLhhyoLH6Ijfyl_VMCsi54UqGQafGkNOQH)
2. The PyTorch Seq2Seq GitHub repository by bentrevett, available at: [GitHub repository](https://github.com/bentrevett/pytorch-seq2seq)
3. Furthermore, Insightful "Deep learning" lectures on Guvi delivered by Sir.

## Question 1
The file contains code for constructing a sequence-to-sequence (seq2seq) model with an RNN architecture. The model consists of the following layers:
- An input layer for character embeddings
- An encoder RNN that sequentially encodes the input character sequence in Latin
- A decoder RNN that takes the final state of the encoder as input and generates one output character at a time in Devanagari

The code is designed to be flexible, allowing the modification of hyperparameters such as the dimension of input character embeddings, hidden states of the encoders and decoders, the type of cell (RNN, LSTM, GRU), and the number of layers in the encoder and decoder.

Note: By simply adjusting the hyperparameter values in the configuration function, you can customize the behavior of the model.

## Question 2
This Python notebook includes code that enables the configuration and execution of wandb sweeps.

### Predictions
- `predictions_vanilla`: Contains all the test data predictions made by the best vanilla model.
- `predictions_attention`: Contains all the test data predictions made by the best attention model.
