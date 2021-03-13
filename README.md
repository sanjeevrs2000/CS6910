# Backpropagation and Optimization algorithms
 
The aim of this project is to implement a backpropagation framework from scratch using only numpy and pandas.
Using this backpropagation framework, various optimization algorithms where written. 

The optimization algorithms where used to train a neutral network on the Fashion MNIST dataset.
The performance on training data by the neural networks with different hyperparameters where recorded and visualizd using WandB's sweep function
and the best performing model was choosen based on validation accuracy.

Open the notebook titled 'Assignment_1_deep_learning_Final.ipynb' to test the code.

Run each cell one by one. Even the MNIST dataset or any other data set can be loaded and tested with the same model as it is flexible.

The input_layer_size and the output_layer_size should be changed based on the dataset being used inside the Train() function.

The dict named 'config_defaults' has default hyperparameter values stored. Change values of the hyperparamters inside this dict to any other valid values.

Feed_forward and Back_propagation functions and all the optimization functions have been defined inside the Train() function.

In the function Train(), wandb.init, wandb.config and wandb.log have been commented so as to do a trial run without logging in wandb.

The Train() returns the trained weights and biases which are used in the test function for prediction.

Run the following block to train the model and run it on test set to get predictions.



