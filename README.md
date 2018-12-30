# KERAS

 KERAS is the API developed on top of Tensor Flow. 
 
---

###  Installing keras 
    conda install keras
---
 
 ## Creating Models in Keras:
  1. Initializing the Model: -sequential() 
  
  2. Adding layers in a model: - Add/Dense()
       Parameters:
        * Activation Function
        * Imput Units(how many neurons/dimensions)
        * Units (in the next layer
        * Kernal/Weights initialization technique(random/uniform,..)
        
  3. Compiling the Model: -compile()
       Parameters :
        * Loss Function (rmse, binaryloss, entropy,..)
        * Optimizer (SGDo, ADAM,..)
        * Metric (accuracy, precision, recall,..)
   --- 
   
   ## Creating a complete Model:
    1. Importing Libraries
    2. Read Dataset
    3. Seperating Dependednt & Independent Variables(x,y)
    4. Preprocessing 
          * Encode categorical variables
          * Data imputation
          * Indentifying outliers
          * Scaling
    5. Split
       * Train
       * Test
    6. Create models in Keras
    7. Fit model on Train set
    8. Test model on Test set
    9. Visualization, Accuracy, Precision, Recall
   10. Hypertuning
   
   
                  
  


