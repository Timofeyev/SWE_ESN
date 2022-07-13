# SWE_ESN
Implementation of the ESN prediction with transfer learning for the SWE; python3

this is the code for the paper https://arxiv.org/abs/2112.09182

swesrc - numerical code the SWE with preiodic BC
esn - implemetation of the ESN training and prediction
test0 ... test9 - testing and training datasets for the SWE; each test containg 31 runs of SWE with different initial conditions; test0 = benchmark dataset with H0=4, and U0=2.5
esnres - results of the ESN prediction for each testing dataset
