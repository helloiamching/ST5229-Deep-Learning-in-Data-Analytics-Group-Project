This project examines the ResNeSt deep learning architecture, a model that builds on previous works like ResNet, ResNeXt, and SE-Net. 
We explore its core innovation: the Split-Attention block, which cleverly combines grouped convolutions (cardinality) with an attention mechanism across different feature map splits (radix). 
Through experiments on the CIFAR-10 dataset, including parameter variations (ablation) and comparisons with other networks, we assessed ResNeSt's performance.
A transfer learning task was also conducted to test its feature extraction strength compared with ResNet-50. 
Our findings show that ResNeSt offers competitive accuracy and in particular robust feature learning capabilities which is suitable for downstream tasks, although its design adds complexity compared to simpler residual networks.
