# Concrete Strength Regression

This project demonstrates the use of deep learning techniques to predict the compressive strength of concrete based on the volumes of its ingredients. The dataset used in this project contains information about various ingredients and their proportions, including:

- Cement
- Blast furnace slag
- Fly ash
- Water
- Superplasticizer
- Coarse aggregate
- Fine aggregate

## Project Overview

The project involves the following steps:

1. **Data Preprocessing**:
   - Loading the dataset.
   - Checking for missing values and performing exploratory data analysis.
   - Splitting the data into predictors and target variables.
   - Normalizing the predictors.

2. **Model Building**:
   - Building a regression model using Keras with two hidden layers, each containing 50 nodes and ReLU activation functions.
   - Compiling the model using the Adam optimizer and mean squared error as the loss function.

3. **Training and Testing**:
   - Training the model on the normalized predictors and target values.
   - Validating the model using a validation split.

4. **Extended Model**:
   - Recreating the regression model with five hidden layers, each containing 50 nodes and ReLU activation functions, to improve performance.

## Key Features

- **Deep Learning Framework**: The project uses TensorFlow and Keras for building and training the neural network models.
- **Data Normalization**: Ensures that the input features are scaled for better model performance.
- **Customizable Architecture**: The neural network architecture can be easily modified to experiment with different configurations.

## How to Run

1. Clone the repository to your local machine.
2. Install the required Python libraries:
   ```
   pip install pandas numpy keras tensorflow
   ```
3. Open the Jupyter Notebook file `Concrete_Strength_Regression.ipynb`.
4. Run the cells sequentially to preprocess the data, build the model, and train it.

## Results

The project demonstrates how deep learning can be effectively used for regression tasks. By experimenting with different architectures, the model's performance can be optimized for better predictions.

## Dataset

The dataset used in this project is publicly available and can be accessed [here](https://s3-api.us-geo.objectstorage.softlayer.net/cf-courses-data/CognitiveClass/DL0101EN/labs/data/concrete_data.csv).

## Dependencies

- Python 3.x
- TensorFlow
- Keras
- Pandas
- NumPy

## Acknowledgments

This project is part of the Deep Learning course by Cognitive Class. Special thanks to the course creators for providing the dataset and guidance.

## License

This project is licensed under the MIT License. Feel free to use and modify the code as needed.
