# Density-Encoding-Enables-Resource-Efficient-Randomly-Connected-Neural-Networks

We provide Matlab implementation of the study called "Density Encoding Enables Resource-Efficient Randomly Connected Neural Networks"

These programs are licensed as GNU GPLv3.

The current version of code covers all experiments reported in Figures 5-7 as well as hardware implementations of the considered approaches, which was used for Figure 7.

The code and README file for FPGA design could be found in folder Experiment_3/FPGA_hardware.

DEPENDENCIES for experiments to obtain classification accuracy:

Matlab 2018b or later
Matlab Deep Learning Toolbox
Matlab Optimization Toolbox
Matlab Communications Toolbox


HOW TO:
	In each folder the name of the main script is META_RUN. It runs the necessary scenarios and functions. 

Note that not all datasets are not provided. They are accessible via http://persoal.citius.usc.es/manuel.fernandez.delgado/papers/jmlr/data.tar.gz. Please extract them into a folders “many_datasets” for each corresponding experiment.  
The folders include only 2 datasets in order to demonstrate that the code works. Note also, that in order to start experiment 3 one first needs to do FPGA simulations and obtain possible size of the model for the given energy budget.



Please let us know if you face any problem or discover any bugs!
For more info, you can read our paper once it is available.
Thanks!

Denis Kleyko
email: denis.kleyko@gmail.com
