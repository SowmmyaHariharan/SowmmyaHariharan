Project Strategy
Baseline Model:
Start with an initial model configuration, selecting techniques such as ReLU, ADAM, Batch Normalization, L2 Regularization, and Dropout.

Optimization Process:
Learning Rate Scheduling: Explore different scheduling methods and choose the most effective one.
Activation Functions: Compare various activation functions and select the best-performing one.
Optimizers: Evaluate the performance of different optimizers and pick the most suitable one.
Continue Exploring Techniques: Iterate this process to explore other techniques such as regularization and dropout.
The goal is to progressively improve the model’s performance compared to the initial baseline configuration by exploring and combining these techniques.

Hyperparameter Tuning
While building both the MLP and CNN models, you will need to fine-tune key hyperparameters to achieve the best results, such as:

Number of hidden layers.
Number of neurons in each hidden layer.
Training Steps:
Import Libraries: Use necessary libraries such as NumPy, pandas, PyTorch, or TensorFlow.
Load the Dataset: Use the PyTorch dataset library to download and load the EMNIST dataset.
Split Data: Split the dataset into training and testing subsets using data loaders (e.g., DataLoader in PyTorch).
Dataset Visualization: Visualize the data by plotting sample images and printing out the number of training and testing samples.
Model Development and Evaluation:
Cross Validation: Use cross-validation to find the most suitable combination of techniques and hyperparameters for each model.
Best Model Selection: After determining the best-performing model (for both MLP and CNN), do the following:
Plot Loss Graph: Plot the loss over iterations/epochs.
Plot Accuracy Graph: Plot the accuracy over iterations/epochs.
Print Training Time: Report the time taken for training on both CPU and GPU (if applicable)
