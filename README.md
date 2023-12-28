GraphGST: Graph Generative Structure-Aware Transformer for Hyperspectral Image Classification
------------------------------------------------
Authors: Mengying Jiang, Yuanchao Su, Lianru Gao, Antonio Plaza, Xi-Le Zhao, Guizhong Liu, and Xun Sun
python main.py --dataset Indian --epoches 400 --batch_size 64 --dropout 0.2
--nlayers 9 --window_a 5 --window_b 11 --r_positive 0.1 --lambdas 5

python main.py --dataset WHU_Hi_LongKou --epoches 400 --batch_size 512 --dropout 0.5
 --nlayers 3 --window_a 7 --window_b 11  --r_positive 0.2 --lambdas 10

python main.py --dataset Houston2013 --epoches 400 --batch_size 512 --dropout 0.4
--nlayers 3 --window_a 5 --window_b 9 --r_positive 0.2 --lambdas 5
