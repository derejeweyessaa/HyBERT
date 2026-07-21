HyBERT/
│
├── README.md
├── LICENSE
├── requirements.txt
├── environment.yml
├── setup.py
├── .gitignore
├── config.py
├── train.py
├── evaluate.py
├── predict.py
├── inference.py
│
├── models/
│   ├── hybert.py
│   ├── bert_encoder.py
│   ├── hyperbolic_embedding.py
│   ├── tangent_mapping.py
│   ├── codewise_attention.py
│   ├── classifier.py
│   └── loss.py
│
├── datasets/
│   ├── dataset.py
│   ├── preprocessing.py
│   └── split_dataset.py
│
├── trainer/
│   ├── trainer.py
│   ├── evaluator.py
│   └── statistics.py
│
├── utils/
│   ├── metrics.py
│   ├── visualization.py
│   └── helper.py
│
├── checkpoints/
│   └── hybert_best.pt
│
├── notebooks/
│   └── HyBERT_Demo.ipynb
│
├── figures/
│   ├── architecture.png
│   ├── umap.png
│   └── attention_heatmap.png
│
└── data/
    └── README.md

HyBERT architecture includes:

BERT encoder (e.g  base BERT)
Hyperbolic (Poincaré ball) ICD embeddings
Tangent-space mapping (LogMap)
Code-wise attention mechanism
Riemannian optimization (Geoopt RiemannianAdam)
Multi-label ICD prediction
UMAP visualization
Ablation study variants
PyTorch + Hugging Face Transformers
MIMIC-III/NCoD datasets

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

Part 1

config.py
main.py
train.py
evaluate.py

Part 2

models/hybert.py
ClinicalBERT encoder
Hyperbolic ICD embeddings
Tangent-space mapping
Code-wise attention

Part 3

Geoopt Poincaré manifold
Riemannian optimizer
Möbius operations
Log and Exp maps

Part 4

MIMIC-III dataloader
NCoD dataloader
Tokenization
ICD hierarchy construction

Part 5

Metrics
AUROC
Micro/Macro F1
UMAP visualization
Attention heatmaps

Part 6

Streamlit demo
Prediction API
Inference script
Model checkpoint loading

This  produced complete research
