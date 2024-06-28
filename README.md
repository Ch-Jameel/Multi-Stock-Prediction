# Multi-Stock-Prediction

- **Integrated historical stock data for multiple companies**:
  - Consolidated data for various companies including Apple, Google, Microsoft, and Amazon into a single dataframe.
  - Ensured consistent formatting and handled missing values to maintain data integrity.

- **Comprehensive data preprocessing**:
  - Converted dates to datetime objects, calculated daily returns, and normalized features using MinMaxScaler.
  - Arranged data into sequences with appropriate dimensions: \( x \) (input sequences) and \( y \) (predicted values).

- **Developed multi-company workflow**:
  - Utilized a loop to preprocess and train models for each company's stock data separately.
  - Implemented a function to handle model training and evaluation for different stocks, ensuring scalability and modularity.

- **Model training and prediction**:
  - Constructed and trained LSTM models using TensorFlow and Keras for each company.
  - Implemented early stopping and model checkpoints to optimize performance and prevent overfitting.
  - Predicted stock prices with the model, achieving predictions with dimensions matching the input sequences.

- **Performance evaluation**:
  - Evaluated model performance using metrics such as R-squared and Mean Squared Error (MSE), achieving high accuracy in predictions.
  - Visualized predictions against actual stock prices to validate model effectiveness.
