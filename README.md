Vec2image: an explainable artificial intelligence model for feature representation and classification of high-dimensional biological data by vector-to-image convention



Vec2image: Vec2image for MATLAB is a free, open-source code for classification and feature selection

(1) Two input files are required: 1) a features-by-samples data table, 2) a list of feature labels. (see Example dataset1 and dataset2).

(2) Main.m is the main program to execute Vec2image algorithm. You can execute the program step by step

(3) Output: The output file res.mat contains the well-trained model in out.mat, the predicted accuracy of test data and  the importance/impact score of each feature.

(4) dataset1 and dataset2 is provide to verify the code.


Note : 

(1) We will use the trainNetwork() function in Matlab when we train a CNN model,  please note your matlab version (>= MTALAB2020a).

(2) You can train on either a CPU or a GPU (makeObjFcn5.m at Line 131). For image classification, you can train a single network in parallel using multiple GPUs or a local or remote parallel pool to save training time. To use a GPU for deep learning, you must also have a supported GPU device.

(3) The MaxEpochs is set to 100 in makeObjFcn5.m at Line 130. Please change this as desired. This will affect the processing time of training.


* Currently, the password of the compressed package can be obtained from the authors, and the package code will be freely accessed here before end of 2022.  

Contact
Email: tanghui2020@scut.edu.cn; zengtao@sibs.ac.cn


##############################################################################################################################################################
* V0.2     Supporting umap now, in addition to kPCA, tSNE

           Supplying the python implementation of ResNet for Vec2image, which is based on PyTorch
##############################################################################################################################################################

Reference:
Tang H, Yu X, Liu R, Zeng T. Vec2image: an explainable artificial intelligence model for the feature representation and classification of high-dimensional biological data by vector-to-image conversion. Brief Bioinform. 2022 Jan 31:bbab584. doi: 10.1093/bib/bbab584. PMID: 35106553
