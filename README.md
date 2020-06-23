# Linear-Regression-using-PyTorch
The learning part of linear regression is to figure out a set of weights w11, w12,... w23, b1 &amp; b2 by looking at the training data, to make accurate predictions for new data (i.e. to predict the yields for apples and oranges in a new region using the average temperature, rainfall and humidity). This is done by adjusting the weights slightly many times to make better predictions, using an optimization technique called gradient descent

# Topics to learn
1. Converting numpy into tensor and vise-versa
2. Concept of weights and baises in model
3. Computing loss function
4. Updating weights and baises using gradients decent in the backpropogation
   a) Generate predictions
   b) Calculate the loss
   c) Compute gradients w.r.t the weights and biases
   d) Adjust the weights by subtracting a small quantity proportional to the gradient
   e) Reset the gradients to zero
   
5. Understading gradients funtion
     If a gradient element is positive:
     increasing the element's value slightly will increase the loss.
     decreasing the element's value slightly will decrease the loss
     
     If a gradient element is negative:
     increasing the element's value slightly will decrease the loss.
     decreasing the element's value slightly will increase the loss.
 
 6. Understaing the concept of epoch and optimizer
