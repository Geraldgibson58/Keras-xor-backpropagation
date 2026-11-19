# XOR Gate Classification Using Keras and Backpropagation

## Project Overview
This project demonstrates the development and evaluation of a Multilayer Perceptron (MLP) neural network using Python and Keras to simulate an XOR (Exclusive-OR) logic gate. The project applies backpropagation, model training, hyperparameter tuning, and classification techniques to evaluate neural network performance.

## Project Objectives
- Explore and prepare XOR classification data.
- Split data into training, validation, and testing sets.
- Develop and train neural networks using Keras.
- Compare multiple classification algorithms.
- Optimize neural network hyperparameters.
- Evaluate accuracy, precision, recall, F1 score, and model loss.
- Generate predictions for all XOR input combinations.

## Technologies Used
- Python
- Keras / TensorFlow
- Scikit-learn
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

## Machine Learning Models
The project compares logistic regression, decision trees, k-nearest neighbors, support vector machines, and four Keras MLP configurations.

The selected neural network uses a 2–4–1 architecture with a tanh hidden activation, sigmoid output, Adam optimizer, and binary cross-entropy loss.

## Model Performance

| Evaluation Metric | Result |
|---|---|
| Accuracy | 100% |
| Precision | 100% |
| Recall | 100% |
| F1 Score | 100% |
| Test Log Loss | 0.001149 |

### XOR Predictions

| Input 1 | Input 2 | Expected | Predicted |
|---|---|---|---|
| 0 | 0 | 0 | 0 |
| 0 | 1 | 1 | 1 |
| 1 | 0 | 1 | 1 |
| 1 | 1 | 0 | 0 |

The selected neural network correctly classified all four XOR input combinations.

## Visualizations
The project includes training and validation loss curves, a confusion matrix, an XOR input visualization, and a neural network decision surface.

## Running the Project
1. Install Python and Jupyter Notebook.
2. Install the required packages using `pip install keras tensorflow scikit-learn numpy pandas matplotlib jupyter`.
3. Open `ANA_675_XOR_Keras_Backpropagation_Completed.ipynb`.
4. Execute all notebook cells to reproduce the training, evaluation, and predictions.

## Limitations
XOR contains only four unique input combinations. The training, validation, and testing datasets include repeated instances of these combinations. Therefore, the reported accuracy demonstrates successful learning of the XOR truth table rather than generalization to unseen input combinations.

## Conclusion
This project demonstrates how neural networks can learn nonlinear relationships through backpropagation. By comparing classification algorithms and tuning neural network configurations, the analysis illustrates fundamental machine learning concepts, model optimization, and performance evaluation.

**Academic Project:** ANA-675, Module 2
