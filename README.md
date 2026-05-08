# part-1-neural-network-analysis
 Neural Network Fundamentals and Training Behavior Analysis 

## Project Overview
This project focuses on building and analyzing a feed-forward neural network model using a structured customer churn dataset. The main objective is to understand how neural networks learn patterns from data through forward propagation, loss calculation, backpropagation, and parameter updates.

The project includes complete data preprocessing, neural network model building, model evaluation, and hyperparameter experimentation using TensorFlow/Keras.

### Task 1: Dataset Understanding
- Loaded and explored the dataset
- Checked dataset shape, columns, and data types
- Performed missing value analysis
- Generated statistical summary
- Visualized target variable distribution

### Task 2: Data Preprocessing
- Removed unnecessary identifier column
- Encoded categorical variables using one-hot encoding
- Performed train-test split
- Applied feature scaling using StandardScaler

### Task 3: Neural Network Model Building
- Built a feed-forward neural network using TensorFlow/Keras
- Used ReLU activation in hidden layer
- Used Sigmoid activation in output layer
- Compiled model with Adam optimizer and Binary Crossentropy loss

### Task 4: Training and Evaluation
- Trained the neural network model
- Evaluated training and testing performance
- Generated confusion matrix and classification report
- Visualized accuracy and loss curves

### Task 5: Hyperparameter Experimentation
- Conducted multiple experiments with different configurations
- Compared performance using different neurons and learning rates
- Saved comparison results in CSV and PNG format

### Task 6: Final Reflection
- Explained the role of weights and biases
- Discussed importance of activation functions
- Analyzed effects of learning rate
- Identified signs of overfitting and underfitting

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras
