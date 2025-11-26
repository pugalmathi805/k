1. Choose or create a multivariate time-series dataset

You must use a dataset with:

at least 5 features

at least 1000 observations

clear patterns such as seasonality, trends, or noise

You may download a real dataset or generate a synthetic one yourself.

2. Build a high-quality attention-based forecasting model

Write clean Python code (with PyTorch or TensorFlow/Keras) to implement a model such as:

a Transformer encoder, or

an LSTM with attention

Your code should follow good production standards: modular, readable, and reproducible.

3. Train the model and tune the hyperparameters

You should:

optimize learning rate, number of layers, attention heads, sequence length, etc.

ensure proper time-series validation (no future data leakage)

The goal is to train the attention model effectively and responsibly.

4. Build two baseline models for comparison

You must train:

A traditional model (e.g., SARIMA or Prophet)

A standard LSTM without attention

This allows you to compare how attention-based models improve forecasting performance.

5. Analyze the attention weights

After training, study how the model distributes its attention across:

different input features

different past time steps

You must also provide visualizations (e.g., heatmaps) to show how the model focuses on information.

1. Production-grade Python code

Your code should handle:

loading the dataset

preprocessing

defining all models

training loops

evaluation

visualizations

Everything must run without errors.

2. A thorough technical report

You must write a detailed explanation describing:

why you chose your model architecture

how you tuned hyperparameters

what design decisions you made

what challenges you met

This shows your understanding of the project.

3. A performance comparison

Provide a clear summary comparing:

the attention model

the LSTM baseline

the SARIMA/Prophet baseline

Use metrics such as RMSE, MAE, and directional accuracy—and discuss which model performs better and why.

4. Attention visualization & interpretation

Finally, include:

attention heatmaps

plots showing how the model uses past data

written interpretation explaining what the attention patterns mean

This demonstrates the interpretability of the model.
