#Apple Stock Price Prediction Using LSTM

Overview
This project aims to predict Apple Inc. (AAPL) stock prices using Long Short-Term Memory (LSTM) neural networks. We explore the stock price data, preprocess it, and build an LSTM model to forecast future prices. The model is built using Keras and TensorFlow, and the project ensures reproducibility through proper random seed settings.

Using the Jupyter Notebook
You can explore the data and train the model using the provided Jupyter notebook:
bash
Copy code
jupyter notebook notebooks/apple_stock_prediction.ipynb
The notebook includes steps for data exploration, preprocessing, model building, training, and evaluation.

Reproducibility
To ensure reproducibility, the following random seeds are set in the project:
NumPy: np.random.seed(7)
These seeds ensure that the results are consistent across different runs.

Results
After training the model, results such as loss and accuracy will be displayed. The trained model is saved in the models directory. You can load and evaluate the model using the saved file.

Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes. 
