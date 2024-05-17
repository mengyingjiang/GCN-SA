# GCN-SA
This code is for the paper "Self-Attention Empowered Graph Convolutional Network for Structure Learning and Node Embedding"
This paper has been published on Pattern Recognition.

Cora
Train_Vain_Test: 48%_32%_20%
python train.py  --dataset cora --dropout 0.55 --hd 48 --K 4 --seed 42 --wd 5e-4 --lr 0.03 --epsilon 0.95 --r 5 --trainsplit 0.48 
Train_Vain_Test: 60%_20%_20%
python train.py  --dataset cora --dropout 0.50 --hd 48 --K 4 --seed 42 --wd 5e-4 --lr 0.03 --epsilon 0.95 --r 5 --trainsplit 0.60 
--------------------------------------------------------------------------------------------------------------------------------
Citeseer
Train_Vain_Test: 48%_32%_20%
python train.py  --dataset citeseer --dropout 0.55 --hd 48 --K 3 --seed 42 --wd 5e-4 --lr 0.03 --epsilon 0.95 --r 3 --trainsplit 0.48
Train_Vain_Test: 60%_20%_20%
python train.py --dataset citeseer --dropout 0.5 --hd 48 --K 3 --seed 42 --wd 5e-4 --lr 0.03 --epsilon 0.95 --r 3 --trainsplit 0.60
------------------------------------------------------------------------------------------------------------------------------------
Pubmed
Train_Vain_Test: 48%_32%_20%
python train.py  --dataset pubmed --dropout 0.55 --hd 32 --K 2 --seed 42 --wd 5e-4 --lr 0.03 --epsilon 0.95 --r 3 --trainsplit 0.48
Train_Vain_Test: 60%_20%_20%
python train.py  --dataset pubmed --dropout 0.55 --hd 32 --K 2 --seed 42 --wd 5e-4 --lr 0.03 --epsilon 0.95 --r 3 --trainsplit 0.60 
------------------------------------------------------------------------------------------------------------------------------------
Squirrel
Train_Vain_Test: 48%_32%_20%
python train.py  --dataset squirrel --dropout 0.55 --hd 48 --K 2 --seed 42 --wd 5e-4 --lr 0.05 --epsilon 0.9 --r 3 --trainsplit 0.48
Train_Vain_Test: 60%_20%_20%
python train.py  --dataset squirrel --dropout 0.55 --hd 48 --K 2 --seed 42 --wd 5e-4 --lr 0.05 --epsilon 0.9 --r 3 --trainsplit 0.60 
------------------------------------------------------------------------------------------------------------------------------------
Chameleon
Train_Vain_Test: 48%_32%_20%
python train.py  --dataset chameleon --dropout 0.55 --hd 32 --K 2 --seed 42 --wd 5e-4 --lr 0.05 --epsilon 0.85 --r 3 --trainsplit 0.48
Train_Vain_Test: 60%_20%_20%
python train.py  --dataset chameleon --dropout 0.55 --hd 32 --K 2 --seed 42 --wd 5e-4 --lr 0.05 --epsilon 0.85 --r 3 --trainsplit 0.60
------------------------------------------------------------------------------------------------------------------------------------
Cornell
Train_Vain_Test: 48%_32%_20%
python train.py  --dataset cornell --dropout 0.2 --hd 64 --K 5 --seed 42 --wd 5e-2 --lr 0.02 --epsilon 0.95 --r 3 --trainsplit 0.48
Train_Vain_Test: 60%_20%_20%
python train.py  --dataset cornell --dropout 0.2 --hd 64 --K 5 --seed 42 --wd 5e-2 --lr 0.02 --epsilon 0.95 --r 3 --trainsplit 0.60
------------------------------------------------------------------------------------------------------------------------------------
Texas
Train_Vain_Test: 48%_32%_20%
python train.py  --dataset texas --dropout 0.2 --hd 48 --K 1 --seed 42 --wd 5e-2 --lr 0.02 --epsilon 0.85 --r 3 --trainsplit 0.48
Train_Vain_Test: 60%_20%_20%
python train.py  --dataset texas --dropout 0.2 --hd 48 --K 1 --seed 42 --wd 5e-2 --lr 0.01 --epsilon 0.85 --r 3 --trainsplit 0.60
------------------------------------------------------------------------------------------------------------------------------------
Wisconsin
Train_Vain_Test: 48%_32%_20%
python train.py  --dataset wisconsin --dropout 0.35 --hd 48 --K 1 --seed 42 --wd 5e-2 --lr 0.01 --epsilon 0.8 --r 3 --trainsplit 0.48
Train_Vain_Test: 60%_20%_20%
python train.py  --dataset wisconsin --dropout 0.35 --hd 48 --K 1 --seed 42 --wd 5e-2 --lr 0.01 --epsilon 0.8 --r 3 --trainsplit 0.60 
