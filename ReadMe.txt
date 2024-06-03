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
    
    There is little difference in accuracy between iteration 1 and iteration 2.  The use of 32 filters is
    less computationally expensive than the use of 64 filters.
    
    
In Iteration 3,
    The hyperparameters are the same as those in Itereation 2 but with a third convolutional layer. 
    There was only two in iteration 2. This change resulted in less accurate results.
    
    After the model was trained: 
        val_loss: 0.0562, val_accuracy: 0.9782
        

In Itereation 4,
    The hyperparameters are the same as that of iteration 2 with one exception. Gradient descent was used as 
    the optimizer instead of 'adam'.  This resulted in lower accuracy.
    
    After the model was trained:
        val_loss: 0.1405, val_accuracy: 0.9631
        
        
Conclusion: Iteration 2 is the best model to go with because  
    1. It is almost as accurate as iteratioon 1, but less compuatationaly expensive.
    2. It is more accurate and less computationally expensive than either iteration 3 or iteration 4.
  

        
        
        
        



    
    





