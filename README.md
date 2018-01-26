# Outline of Machine Learning Study

Pre-studied basic knowledge: Linear Algebra, Pattern Recognition, Computer Vision

### week 1: Introduction of Deep Learning

Followed [the course of Machine Learning]  <http://speech.ee.ntu.edu.tw/~tlkagk/courses_ML17_2.html>  by Professor Hungyi Lee: 

Three Steps for Deep Learning:

1. Neural network: decide the network structure to
   let a good function in your function set.
2. Goodness of function: make the loss of all samples as small as possible.
3. Pick the best function: find network parameters that minimize the total loss.



#### Neural Networks

DNN (Deep) 

CNN (Convolution): to simplify the network for **image input**.

R-CNN (Region-based CNN): **localize** the region first, then input into CNN.

Fast R-CNN: improve R-CNN's performance by better design and strategies.

Faster R-CNN: RPN (Region Proposal Networks) + Fast R-CNN, and these two parts **share** some CNN layers.

// details



#### Goodness 

Use the loss (sum of the error of each output) to evaluate the goodness. 



#### Pick the Best

Use **Gradient Descent** to train the network parameters (weights and biases) to get a minimal total loss.

Use **Back Propagation** (Forward Pass & Backward Pass) to calculate the partial derivative needed in Gradient Descent. 

