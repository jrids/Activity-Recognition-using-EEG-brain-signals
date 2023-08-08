# Activity-Recognition-using-EEG-brain-signals
Advances in neurotechnology have enhanced and simplified our ability to research brain activity with low-cost and effective equipment. One such scalable and noninvasive technique is Electroencephalography (EEG), which detects and records electrical brain activity. Brain activity recognition is one of the emerging problems as EEG wearables become more readily available. Our research has modeled EEG signals to classify three states (i) music listening, (ii) movie watching, and (iii) meditating. The datasets incorporating the brain signals induced while performing these activities are NMED-T for music listening, SEED for movie watching, and VIP_Y_HYT for meditating. EEG activity is transformed into deep representation using a convolutional neural network comprising three different types of 2D convolutions: Temporal, Spatial, and Separable, to capture dependencies and extract high-level features from the data. The Depthwise Convolution function is responsible for learning spatial filters within each temporal convolution, and combining these spatial filters across all temporal bands optimally is learned by the Separable Convolutions. EEGNet and EEGNet-SSVEP are specially designed for EEG Signal Processing and Classification, and the DeepConvNet has incorporated more convolution layers. Our finding demonstrates that increasing the number of layers in the Network provided a higher accuracy of 99.94% using DeepConvNet. In contrast, the accuracy of EEGNet and EEGNet-SSVEP resulted in 85.63% and 75.76%, respectively.
#### https://ieeexplore.ieee.org/document/10100986
