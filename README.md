<!DOCTYPE html>
<html>

<head>
    <title>cs6910_assignment-3</title>
</head>

<body>
    <h1>cs6910_assignment-3</h1>
    <p>Wandb Report Link: <a href="https://wandb.ai/cs22m024/dl_assignement_3/reports/CS6910-Assignment-3-CS22M024--Vmlldzo0NDA5ODQ4">https://wandb.ai/cs22m024/dl_assignement_3/reports/CS6910-Assignment-3-CS22M024--Vmlldzo0NDA5ODQ4</a></p>
    
    <h2>Inspiration Sources:</h2>
    <ul>
        <li>Aladdin Pearson's YouTube playlist on Seq2Seq Model, which can be accessed at: <a href="https://www.youtube.com/watch?v=EoGUlvhRYpk&list=PLhhyoLH6Ijfyl_VMCsi54UqGQafGkNOQH">YouTube playlist on Seq2Seq Model</a></li>
        <li>The PyTorch Seq2Seq GitHub repository by bentrevett, available at: <a href="https://github.com/bentrevett/pytorch-seq2seq">GitHub repository</a></li>
        <li>Furthermore, Insightful "Deep learning" lectures on Guvi delivered by Sir.</li>
    </ul>

    <h2>Question 1:</h2>
    <p>The file contains code for constructing a sequence-to-sequence (seq2seq) model with an RNN architecture. The model consists of the following layers:</p>
    <ol>
        <li>An input layer for character embeddings</li>
        <li>An encoder RNN that sequentially encodes the input character sequence in Latin</li>
        <li>A decoder RNN that takes the final state of the encoder as input and generates one output character at a time in Devanagari</li>
    </ol>
    <p>The code is designed to be flexible, allowing the modification of hyperparameters such as the dimension of input character embeddings, hidden states of the encoders and decoders, the type of cell (RNN, LSTM, GRU), and the number of layers in the encoder and decoder. <br>Note: By simply adjusting the hyperparameter values in the configuration function, you can customize the behavior of the model.</p>

    <h2>Question 2:</h2>
    <p>This Python notebook includes code that enables the configuration and execution of wandb sweeps.</p>
</body>

</html>
