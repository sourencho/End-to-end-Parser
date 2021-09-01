# vortan_models

## vortan_pos_model_hy.pkl

todo

## vortan_pos_model_hyw.pkl

[Notebook](./train_vortan_pos_model_hyw.ipynb)

Cmd:
```
! python3 -m src.main \
    --mode autotrain \
    --train UD_Western_Armenian-ArmTDP/hyw_armtdp-ud-train.conllu \
    --valid UD_Western_Armenian-ArmTDP/hyw_armtdp-ud-test.conllu \
    --model souren_model.pkl \
    --force_trees \
    --epochs 30
```

Results:
```
UAS: 0.4502355712603062
LAS: 0.2947585394581861
LEMMA: 0.7528464860620337
POS: 0.7324303101688261
XPOS: 1.0
FEAT: 0.39016489988221437
SEM: 1.0
EM: 0.0
Cycle: -1
```
