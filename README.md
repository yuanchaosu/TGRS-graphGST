GraphGST: Graph Generative Structure-Aware Transformer for Hyperspectral Image Classification
------------------------------------------------
Authors: Mengying Jiang, Yuanchao Su*, Lianru Gao, Antonio Plaza, Xi-Le Zhao, Xu Sun, and Guizhong Liu

Implementation Details:
The proposed GraphGST is implemented with the DL library PyTorch. 
The Python and PyTorch versions are 3.8.10 and 1.9.0, respectively.
We use the ReLU activation function and Adam optimizer by default. 
All experiments are conducted on a Windows server with a graphics processing unit (GPU) (NVIDIA GeForce RTX 4090).

Our GraphGST model was completed on May 20, 2023. 
It is a powerful Transformer model designed specifically for hyperspectral data.
Our manuscript was completed on September 26, 2023.

python main.py --dataset Indian --epoches 400 --batch_size 64 --dropout 0.2
--nlayers 9 --window_a 5 --window_b 11 --r_positive 0.1 --lambdas 5

python main.py --dataset WHU_Hi_LongKou --epoches 400 --batch_size 512 --dropout 0.5
 --nlayers 3 --window_a 7 --window_b 11  --r_positive 0.2 --lambdas 10

python main.py --dataset Houston2013 --epoches 400 --batch_size 512 --dropout 0.4
--nlayers 3 --window_a 5 --window_b 9 --r_positive 0.2 --lambdas 5

python main.py --dataset Houston2018 --epoches 800 --batch_size 64 --dropout 0.5
--nlayers 9 --window_a 7 --window_b 9  --r_positive 0.1 --lambdas 10
