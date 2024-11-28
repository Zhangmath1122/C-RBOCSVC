# C-RBOCSVC
C-Parameter Version of Robust Bounded One-class Support Vector Classification
C-Parameter Version of Robust Bounded One-class Support Vector Classification
File Description:
BOCSVC_pre.m: To train the proposed method C-BOCSVC, the input parameters required are: regularization parameter C, kernel parameter p, kernel function type ker, and training data X.
BOCSVC_test.m: Calculated assessment criteria are based on predicted results and real labels for the proposed C-BOCSVC.
RBOCSVC_pre.m: To train the proposed method C-RBOCSVC, the input parameters required are: regularization parameter C, kernel parameter p, nearest neighbor parameter K, kernel function type ker, and training data X.
RBOCSVC_test.m: Calculated assessment criteria are based on predicted results and real labels for the proposed C-RBOCSVC.
KNN.m: Calculating the k-nearest neighbor relative density weights, the input parameters required are: kernel function type ker, training data X, nearest neighbor parameter K, compression factor p1, kernel parameter p.
optpara.m/optpara_clean.m: Adjust the optimal parameters on contaminated data or clean data.
Evaluation.m/Evaluation_clean.m: Test program with optimal parameters.
Svkernel.m: The package of kernel functions, the input parameters required are: kernel function type ker, data u, data v, kernel parameter p.
Train_Test_Map.m: Calculation of parameter combinations, enter given ranges for all parameters.
split_data.m: Programs that split data.

The code has been tested on Windows 11 with MATLAB R2022a. For further inquiries, please contact: yejymath@163.com.
