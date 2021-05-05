## Scope

Please find the answers for the assignment 1 of END2.0 course's questions in the below sections.

### What is a neural network neuron?
  Neuron is a mathematical operation takes the input and multiply by it's weight and passes the sum to another neuron via activation function.

### What is the use of the learning rate?
The learning rate is a configurable hyperparameter used in the training of neural networks that has a small positive value.

The learning rate controls how quickly the model is adapted to the problem. A smaller learning rate requires many updates before reaching the minimum point. Too large of a learning rate causes drastic updates which lead to divergent behaviors. So it is always important to choose optimal learning rate swiftly reaches the minimum point.

### What is "loss" in neural network?
  "Loss" is nothing but a prediction error. This is the difference between the expected output and predicted output.

### What is "chain rule" in gradient flow?
  The chain rule can be used to compute the effect of the node on the gradients flowing back from right to left. 
  
  Mathematically total output gradient is the total gradient caused by the two things which can be written as:
  
    FinalGradient=GradientContribution1+GradientContribution2       
    Gradient1=GradientInside×GradientContribution1 
    or
    ∂Output∂wi=∂Contribution1∂wi×∂Output∂Contribution1
