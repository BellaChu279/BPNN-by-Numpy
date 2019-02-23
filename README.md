# BPNN-by-Numpy
The BPNN(Backward Propogation Nerural Networks) is realized by Numpy but not by TensorFlow, MXNet, Caffe or other tools. This work is for fundamental research like optimization in neural networks.

The MNIST data set is adopted for this code which is saved in 'data' file. Additionally, parameters during training procedure are also saved in this file, which is named 'layers_x_y' (x is #Epoch, y is #Iteration of #Epoch). Train log is saved in 'ouput' file with name of date and time.

When the code is run for the first time, there will be a initialized parameters of LeNet saved in 'data' file as 'initial_layers_z'(z is the #Experiment). Therefore, if 'initial_layers_z' exists in 'data' file, the code will read the initial parameters from it when the code is run for next time. Although this function could help you save data or parameters and reproduce experiment, it leads to the same results for different expereiments. If you don't need this function, the 'initial_layers_z' is supposed to be deleted or renamed when starting next experiment.
# BPNN-by-Numpy
