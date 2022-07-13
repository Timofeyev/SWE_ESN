# SWE_ESN
Implementation of the ESN prediction with transfer learning for the SWE; python3

this is the code for the paper https://arxiv.org/abs/2112.09182

swesrc - numerical code the SWE with preiodic BC

esn - implemetation of the ESN training and prediction

test0train, test0test - testing and training datasets for the SWE; 10 and 5 runs of SWE with different initial conditions; these two directories can be combined into a signle test0 directory. test0 = benchmark dataset with H0=4, and U0=2.5; make sure code for esn training uses only 10 directories for training and 5 for testing.
test8train, test8test - same for data with H0=4.4, and U0=2.5 and use for transfer learning

esnres - results of the ESN prediction need to be regenerated b/c files (in partiuclar, connectivity matrix A) are too big. 
