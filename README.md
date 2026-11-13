# bikelane-conflict-kit

Reference implementation for **"Conflict-Aware Risk Scoring for Urban Bike-Lane Intersections"** (Accident Analysis & Prevention).

This repository contains the complete training and evaluation pipeline used in the
paper: dataset loaders, the model, the training loop, the evaluation script and the
released metrics.

## Contents

```
configs/
  default.yaml
src/
  __init__.py
  risk.py
train.py
eval.py
results/
  metrics.md
requirements.txt
```

## Quick start

```
pip install -r requirements.txt
python train.py --config configs/default.yaml
python eval.py --checkpoint checkpoints/best.pt
```

The released checkpoint reproduces the numbers in `results/metrics.md`.

## Citation

```bibtex
@inproceedings{bikelane-conflict-kit2026,
  title={Conflict-Aware Risk Scoring for Urban Bike-Lane Intersections},
  booktitle={Accident Analysis & Prevention},
  year={2026}
  
}
```
