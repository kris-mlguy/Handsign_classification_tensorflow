### Image processing - handsign classification

-> Handsign classification is a multi class classification problem based on pictures    

-> The images are saved as numpy arrays   

-> The dataset consists of 1200 examples, with each example having 64 (pixels) x 64 (pixels) x 3 (colors) matrix  

-> The objective is to classify a given picture (in the form of numpy arrays) into numbers from 0 to 5  

Steps: 
1) Flattening the images and normalize image vectors       
2) One hot encoding of labels  
3) Create placeholders and initialize weight matrices  
4) Forward propagation and compute cost  
5) Backpropagation for optimization of weights
6) Run the optimizer and cost functions within a tensorflow session  
7) Run the optimizer using minibatches from training set for a number of epochs until the cost is sufficiently reduced and weights are optimized  
8) Calculate accuracy for training and test sets  


