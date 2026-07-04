# HyBERT
Model the upgrade HyBERT using tangent space and Ramminnian Adam
HyBERT/
│
├── train.py
├── test.py
├── predict.py
├── config.py
├── requirements.txt
│
├── models/
│   ├── hybert.py
│   ├── bert_encoder.py
│   ├── poincare.py
│   ├── tangent.py
│   ├── fusion.py
│   ├── attention.py
│   ├── classifier.py
│   └── loss.py
│
├── datasets/
│   ├── mimic_loader.py
│   ├── ncod_loader.py
│   ├── preprocessing.py
│   └── tokenizer.py
│
├── trainer/
│   ├── trainer.py
│   ├── evaluator.py
│   └── optimizer.py
│
├── utils/
│   ├── metrics.py
│   ├── visualization.py
│   ├── heatmap.py
│   └── umap.py
│
└── checkpoints/
