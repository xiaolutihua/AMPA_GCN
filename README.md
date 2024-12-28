# AMPA_GCN
Enhancing Recommendation Performance using Attribute-aware Message-Passing and Augmentation GCN

# AMPA_GCN
Tensorflow-gpu version: 1.15.15

# Example to run the codes.
python AMPA_GCN.py --dataset gowalla  --regs [1e-4] --embed_size 64 --layer_size [64,64,64,64,64,64] --lr 0.001 --batch_size 2048 --epoch 2000 --groups 3 --Ks [20,10] --gpu_id 0
