# AGT: Enhancing Many-Body Interactions in Material Property Prediction



## Installation

See [installation instructions](https://github.com/nnn66yx/AGT/INSTALL.md).

## Download data

Dataset download links and instructions are in [DATASET.md](https://github.com/nnn66yx/AGT/DATASET.md).

## Train and evaluate models

A detailed description of how to train and evaluate models, run ML-based
relaxations, and generate EvalAI submission files can be found in
[TRAIN.md](https://github.com/nnn66yx/AGT/TRAIN.md).

```
python main.py --mode train --config-yml configs/IS2RE/10k/agt/agt.yml
```

## Pretrained model weights

We provide several pretrained model weights for download
[here](https://github.com/Open-Catalyst-Project/ocp/blob/main/MODELS.md).

## Acknowledgement ##

Our implementation is based on [PyTorch](https://pytorch.org/), [PyG](https://pytorch-geometric.readthedocs.io/en/latest/index.html),  [ocp](https://github.com/Open-Catalyst-Project/ocp)).
