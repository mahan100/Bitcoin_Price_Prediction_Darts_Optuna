# Bitcoin Price Prediction with Darts

This project focuses on predicting Bitcoin prices using the Darts library. It employs a range of machine learning models from Darts, including NBEATS, TCN, Transformer, BlockRNN, LR-RNN, XGBoost (XGB), LSTM, and GURU. Additionally, hyperparameter tuning is performed using the Optuna library to optimize these models. Here's a breakdown of the project:

## Models Used:

- **NBEATS**: A deep learning architecture designed for time series forecasting.
- **TCN (Temporal Convolutional Network)**: A specialized architecture for sequence modeling tasks, suitable for time series forecasting.
- **Transformer**: Originally designed for NLP, the Transformer architecture has been adapted effectively for sequence-to-sequence modeling, including time series forecasting.
- **BlockRNN**: A variant of RNN with block processing, enhancing parallelism and efficiency in sequential data modeling.
- **LR-RNN**: A configuration of Long Short-Term Memory (LSTM) with regularization, capable of capturing long-range dependencies in sequences.
- **XGBoost (XGB)**: A gradient boosting algorithm renowned for its performance in structured/tabular data tasks.
- **LSTM (Long Short-Term Memory)**: A type of RNN that excels in sequential data modeling, especially when long-term dependencies are essential.
- **GURU**: A model with specific characteristics that need further clarification.

## Hyperparameter Tuning:

Hyperparameter tuning is carried out using the Optuna library for the following models:

- **TCNMODEL**: Optimizing hyperparameters for the TCN model to achieve the best configuration.
- **RNN (Recurrent Neural Network)**: Including LSTM, BlockRNN, and possibly LR-RNN, with hyperparameter tuning for enhanced performance.
- **LSTM**: Hyperparameter tuning specifically for the LSTM model to improve its forecasting accuracy.
- **GURU**: Tuning hyperparameters of the GURU model for enhanced predictive performance.
- **BLOCKRNN**: Optimization of hyperparameters for the BlockRNN architecture to improve sequence modeling.
- **NBEATS**: Tuning hyperparameters to achieve the best configuration for time series forecasting.
- **TRANSFORMER**: Hyperparameter tuning for the Transformer model to enhance its performance in sequence-to-sequence tasks.
- **XGB (XGBoost)**: Fine-tuning hyperparameters for the XGBoost model, known for its robustness in tabular data tasks.

## Getting Started

To get started with this project, follow these steps:

1. Clone this repository to your local machine.
2. Install the required dependencies and libraries, as specified in the project's documentation.
3. Explore the provided Jupyter notebooks and scripts for model training and hyperparameter tuning.
4. Experiment with different configurations and models to improve Bitcoin price predictions.

## Usage

Detailed usage instructions and examples for running the models and conducting hyperparameter tuning can be found in the project's documentation.

## Contributing

If you'd like to contribute to this project or report any issues, please refer to our [Contributing Guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to explore the models and hyperparameter tuning techniques used in this repository to improve Bitcoin price predictions.
