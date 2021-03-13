# Backpropagation and Optimization algorithms
 
The aim of this project is to implement a backpropagation framework from scratch using only numpy and pandas.
Using this backpropagation framework, various optimization algorithms where written. 

The optimization algorithms where used to train a neutral network on the Fashion MNIST dataset.
The performance on training data by the neural networks with different hyperparameters where recorded and visualizd using WandB's sweep function
and the best performing model was choosen based on validation accuracy.

Open the notebook titled 'Assignment_1_deep_learning_Final.ipynb' to test the code.
Run each cell one by one. Even the MNIST dataset can be loaded and tested with the same model as it is a similar dataset.
The dict named 'config_defaults' has default hyperparameter values stored.
Change values of the hyperparamters inside this dict to any other valid values.
In the function Train(), wandb.init, wandb.config and wandb.log have been commented so as to do a trial run without logging in wandb.
Run the following block to train the model and run it on test set to get predictions.



