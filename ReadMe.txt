Project Objective : Predict if the page is being flipped using a single image. 

Built a Convolutional Neural Network using binary classification to accomplish this task. 

The notebook 'build_CNN' contains the code used to build this model.

Four iterations ran before the best model was selected.

Iteration 1: 
    The hyperparameters were arbitrarily set. 
    There are two convolutional layers, one dense layer and the ouput layer.
    
    After the model was trained: 
        loss: 0.0248, val_accuracy: 0.9950
    
In Iteration 2,
    The hyperparameters are the same as those in Itereation 1 with one exception.  
    On the second convolutional layer the number of filters is 32. It was 64 in in iteration 1.
    
    After the model was trained: 
        loss: 0.0317, val_accuracy: 0.9950
    
    There is little difference in accuracy between iteration 1 and iteration 2.  Since the use of 32 filters is
    less computationally expensive it was used in subsequent iterations.
    
    
In Iteration 3,
    
    





