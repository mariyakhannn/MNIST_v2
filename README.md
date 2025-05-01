
## Description
A from-scratch implementation of a two-layer neural network for MNIST handwritten digit classification, to demonstrate core principles of deep learning without the use of high-level frameworks. The model achieves ~95% accuracy on the test set through:

* ReLU activation in the hidden layer

* Softmax output with cross-entropy loss

* Stochastic Gradient Descent (SGD) optimization

* Vectorized NumPy operations for efficiency

This project was made to apply my understanding of backpropagation, activation functions, and gradient-based learning + more (for details on this project visit this [article](https://medium.com/@mariya.k2022/mathematics-of-neural-networks-0d151b5a557e))

### Key implementation details:
* 784 input nodes (28x28 pixel images) → 128 hidden neurons → 10 output classes

* Forward/backward pass mechanics with chain rule derivations

* Batch training with customizable learning rates

* Performance shows 96.6% test accuracy after 50 epochs (comparable to keras benchmarks)
### Dataset
*   [MNIST Dataset](https://www.kaggle.com/competitions/digit-recognizer)


### Credits: 
* [Samson Zhang](https://youtu.be/w8yWXqWQYmU?si=Pz0FSPw4zwEqGVO3)
* [Dataquest](https://youtu.be/MQzG1hfhow4?si=B_A3TkZztwEURWwB)

