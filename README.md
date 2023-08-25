# Wine_Quality

# Wine Quality Prediction

This project focuses on building a neural network model to predict the quality of wine based on certain features. The dataset used for this project is stored in the `WineQT.csv` file.

## Project Structure

- `WineQT.csv`: Dataset file.
- `Wine_Quality.ipynb`: Jupyter Notebook containing the code.
- `README.md`: This file.

## Getting Started

1. Clone this repository.
2. Download the dataset file [`WineQT.csv`](WineQT.csv) and place it in the project directory.
3. Open the Jupyter Notebook [`Wine_Quality.ipynb`](Wine_Quality.ipynb) to explore and run the code.
4. Install the required libraries using `pip install -r requirements.txt` if necessary.

## Steps in the Notebook

1. **Data Loading and Exploration**
   - Load the dataset using Pandas to understand its structure.
   - Check for any missing values and duplicated entries.

2. **Data Preprocessing**
   - Drop the unnecessary "Id" column.
   - Separate features (X) and target (y) variables.
   - Split the data into training and testing sets.
   - Convert target labels to categorical format using Keras' `to_categorical`.

3. **Building the Neural Network Model**
   - Create a Sequential model using Keras.
   - Add layers with different activation functions to the model.
   - Compile the model using appropriate loss and metrics.

4. **Model Training**
   - Fit the model to the training data.
   - Evaluate the model's performance on the training set.

5. **Model Testing and Evaluation**
   - Make predictions on the test data.
   - Evaluate the model's performance on the test set.
   - Create and visualize a confusion matrix to assess classification accuracy.

## Note

This project aims to provide a simple demonstration of building a neural network for wine quality prediction. For real-world applications, more sophisticated preprocessing techniques and model tuning may be required.

Author: Pickardss
Date: 25/08/2023

I got Help from chatGPT in this project
