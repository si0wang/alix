
CUDA_VISIBLE_DEVICES=0 python train.py algo=ALIX task=dog_stand seed=0 > /cmlscratch/xywang/code/mbpo_mpcrollout/exp_mpc_rollout/exp20.log 2>&1 &

CUDA_VISIBLE_DEVICES=1 python train.py algo=ALIX task=dog_stand seed=1 > /cmlscratch/xywang/code/mbpo_mpcrollout/exp_mpc_rollout/exp20.log 2>&1 &

CUDA_VISIBLE_DEVICES=2 python train.py algo=ALIX task=dog_stand seed=2 > /cmlscratch/xywang/code/mbpo_mpcrollout/exp_mpc_rollout/exp20.log 2>&1 &

CUDA_VISIBLE_DEVICES=3 python train.py algo=ALIX task=dog_stand seed=3 > /cmlscratch/xywang/code/mbpo_mpcrollout/exp_mpc_rollout/exp20.log 2>&1 &

CUDA_VISIBLE_DEVICES=4 python train.py algo=ALIX task=dog_walk seed=0 > /cmlscratch/xywang/code/mbpo_mpcrollout/exp_mpc_rollout/exp20.log 2>&1 &

CUDA_VISIBLE_DEVICES=5 python train.py algo=ALIX task=dog_walk seed=1 > /cmlscratch/xywang/code/mbpo_mpcrollout/exp_mpc_rollout/exp20.log 2>&1 &

CUDA_VISIBLE_DEVICES=6 python train.py algo=ALIX task=dog_walk seed=2 > /cmlscratch/xywang/code/mbpo_mpcrollout/exp_mpc_rollout/exp20.log 2>&1 &

CUDA_VISIBLE_DEVICES=7 python train.py algo=ALIX task=dog_walk seed=3 > /cmlscratch/xywang/code/mbpo_mpcrollout/exp_mpc_rollout/exp20.log 2>&1 &
