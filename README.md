# An ASIC-Based Artificial Neural Network Applied Real-time Speech Recognition (SOPC structure based on Quartus-Altera)

Work for “Develop an Artificial Neural Network (ANN) digital hardware architecture applying Vietnam speech recognition automatically” project funded by Department Science and Technology of Ho Chi Minh City, Vietnam.

We achieved a dynamic VLSI architecture of ANN, which can re-configure both multiple layers and multiply nodes per layer. 

# Project Hierarchy:

- 01_Publications_Docs : Contain published papers and Documentation

   + 01_Publications_Docs/01_An ASIC-Based Artificial Neural Network Applied Real-time Speech Recognition SOPC.pdf : Published paper for the speech recognition system integrated an ASIC-based ANN.

   + 01_Publications_Docs/02_2_Efficient Hardware Architecture for Single Neuron in Artificial Neural Network.pdf  : Published paper for the architecture of a single neural node.

   + 01_Publications_Docs/03_Short_Introduction.pdf : Short Introduction of ANN archiecture. 

- 02_Codes : Contain coding package for the speed recognition system.

- README.md

# Summary:

Section '02_Codes' contains code lines for the system mentioned in Paper_01. 
This system consits Feature Extraction (Mel-Frequency Ceptral Coefficients) and Classifier (Multi-layer perceptron - MLP Model).

  + MFCC feature is implemented by Software (both Matlab and C). Matlab version is for training process on computer, and C version is for SOPC system loading on DE2 Kit (Altera).

  + MLP classifier model is implemented by Verilog HDL. The 'Paper_02' shows how to implement one neural node by Verilog HDL that is integrated in MLP.
