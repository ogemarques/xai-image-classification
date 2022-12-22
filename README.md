# Explainable AI for Image Classification
This repository shows an example of how to use MATLAB to produce post-hoc explanations -- using [Grad-CAM](https://www.mathworks.com/help/deeplearning/ref/gradcam.html) -- for two image classification tasks. 

## Requirements
- [X]  [MATLAB 2022b](https://www.mathworks.com/products/matlab.html) or later
- [X]  [Deep Learning Toolbox](https://www.mathworks.com/products/deep-learning.html)
- [X]  [Deep Learning Toolbox™ Model for GoogLeNet Network support package](https://www.mathworks.com/help/deeplearning/ref/googlenet.html) 
- [ ]  [Parallel Computing Toolbox](https://www.mathworks.com/products/parallel-computing.html) (only required for training using a GPU)

## Suggested steps
1. Download or clone the repository.
2. Open MATLAB.
3. Run the `example.mlx` script and inspect results.

## Additional remarks
- You are encouraged to expand and adapt the example to your needs.
- The choice of pretrained network and hyperparameters (learning rate, mini-batch size, number of epochs, etc.) is merely illustrative.  
- You are encouraged to (use Experiment Manager app to) tweak those choices and find a better solution.
 
