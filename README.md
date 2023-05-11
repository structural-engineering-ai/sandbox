# sandbox :beach_umbrella:
Preliminary trials and studies of artificial intelligent models to infer structural framing layouts from an architectural model. Framebots V0 through V3 developed and used for the presentation (PDF above). The models were generated and executed in Google Colaboratory. Models using Tensorflow are marked with <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg"  width="15" height="15">. Models using Pytorch are marked with <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" width="15" height="15">.
          
### Framebot V0 <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg"  width="15" height="15"> :smiling_imp:	
Reinforcement Learning on single frame. Model never solved.

### Framebot V1  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg"  width="15" height="15"> :office:	
A dense neural network

### Framebot V2 <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg"  width="15" height="15"> :office:	
3D Convolutional Neural Network in a Unet using voxel models

### Framebot V3 <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg"  width="15" height="15"> :office:	
Generative Adversarial Network (GAN) utilizing 3D CNN

### Framebot V4 ☠️
We don't talk about this one....

### Framebot V5 <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" width="15" height="15"> :house:	
Graph Neural Network (GNN) for classifying simple truss types.

### How to use:
1. Framebot Version 0:
   - Only the file is required. No data to generate or train required.
2. Framebot Version 1-3 and 5:
   - Use the generator to create the training and test data.
   - Use the model and update your file paths to train on the generated data.
   - A viewer file is in the folder - just a handy way to see how the model performed - more for show.
   - Use at your own risk 😆. Generator code is very 'raw'. Was for one time use (really needs refactoring). Model code is OK.
