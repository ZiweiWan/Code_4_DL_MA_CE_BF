# Code_4_DL_MA_CE_BF

The CE folder contains the initial channel estimation scheme, whose output is the estimated channel that serves as the input to the subsequent denoising network.

The CENet folder includes three denoising approaches, where tunet, upt, and cnn correspond to the paper’s CENet, AdaFortiTran, and DnCNN, respectively. The denoised results are used as the input to BFNet.

The BFNet folder contains the (corresponding modules/code).

The code can run as long as the input dimensions are consistent with those in the paper. The denoising network and the position-selection/beamforming network can also be used independently.
