# ADFM
In this work, a novel automatic isotropic triangle generation technique is developed by introducing an artificial neural network (ANN) based advancing double-front method (ADFM) to improve the mesh generation efficiency. First, an initial isotropic triangular mesh is generated by the traditional mesh generation method as the training set of ANN. Second, the ADFM is presented in detail to improve the advancing efficiency, including the structure of the ANN to distinguish the different patterns in the advancing procedure. Finally, several typical cases are tested to validate the effectiveness. 
Nngen_backward_2front. Py is a bp algorithm optimization for training neural grids
Nngen_forward_2front. Py is a feedforward training neural network
Nngen_two_front_20210519_mutiair. py is an ADFM algorithm implementation
Nngen_youhua_20210516_mutiair. py is a further optimization of the initial grid generated by the ADFM algorithm
train_data_output.txt is the dataset to train ANN
