As network technology continues to develop, the popularity of various intelligent terminals has accelerated, leading to a rapid growth in the scale of wireless network traffic.
This growth has resulted in significant pressure on resource consumption and network security maintenance. The objective of this paper is to enhance the prediction accuracy of 
cellular network traffic in order to provide reliable support for subsequent base station sleep control or identification of malicious traffic. To achieve this target, a cellular 
network traffic prediction method based on multi-modal data feature fusion is proposed. Firstly, an attributed KNN (K nearest nodes) graph is constructed based on the similarity 
of data features, and the fused high-dimensional features are incorporated into the graph to provide more information for the model. Subsequently, a dual branch spatio-temporal 
graph neural network with attention mechanism (DBSTGNN-Att) is designed for cellular network traffic prediction. Extensive experiments conducted on real-world datasets demonstrate 
that the proposed method outperforms baseline models such as temporal graph convolutional networks (T-GCN) and spatial-temporal self-attention graph convolutional networks (STA-GCN) 
with mean absolute error (MAE) 4.98% and 2.01% lower, respectively. Additionally, ablation experimental results show that the MAE of multi-modal feature fusion using attributed 
KNN graph is 8.54% lower compared to that of traditional undirected graphs.

In this repository you will find a Python implementation of DBSTGNN. The experiments are performed on a well-known intrusion detection datasets, Milan City cellular traffic dataset.

The code will be available upon publication.
