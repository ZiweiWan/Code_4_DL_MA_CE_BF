# Code_4_DL_MA_CE_BF

**Due to GitHub’s file upload size limitations, the archive has been uploaded in parts. After downloading and extracting the initial archive, please place all the part files together and extract them in one time.**

This simulation code package is mainly used to reproduce a part of the results of the following paper [1]：

[1] K. Feng, Z. Wan, A. Liao, W. Ma, L. Zhu, Z, Xiao, Z, Gao, and R, Zhang, "Deep learning based Channel Estimation and Beamforming in Movable Antenna Systems," submitted to IEEE Transactions on Vehicular Technology, 2026.

Available at: https://arxiv.org/abs/xxxx.xxxx

The CE folder contains the initial channel estimation scheme, whose output is the estimated channel that serves as the input to the subsequent denoising network.

The CENet folder includes three denoising approaches, where tunet, upt, and cnn correspond to the paper’s CENet, AdaFortiTran, and DnCNN, respectively. The denoised results are used as the input to BFNet.

The BFNet folder contains the (corresponding modules/code).

The code can run as long as the input dimensions are consistent with those in the paper. The denoising network and the position-selection/beamforming network can also be used independently.
