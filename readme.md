##HateQwen: A Novel Approach for Hate Speech Detection##

HateQwen is an advanced hate speech detection model based on the Qwen2-1.5 model, fine-tuned using the Low-Rank Adaptation (LoRA) architecture and the dynaHate dataset. This approach has led to significant improvements in accuracy and F1 score, outperforming several prominent models like TinyLLaMA, OPT-1.3B, and phi-2.

Key Features: 

Model: Qwen2-1.5, fine-tuned using the LoRA architecture.
Dataset: dynaHate, a comprehensive dataset for hate speech detection.

Performance:
Accuracy: 84%
F1 Score: 85%

Benchmarking: Superior performance compared to models like TinyLLaMA, OPT-1.3B, and phi-2.

Installation:

Prerequisites
Python 3.x
PyTorch
Transformers

HateQwen was tested on the dynaHate dataset, achieving:
Accuracy: 84%
F1 Score: 85%
This marks a notable improvement over existing models.

Model Comparison:
Model	Accuracy	F1 Score
HateQwen	84%	    85%
TinyLLaMA	71%	    72%
OPT-1.3B	73%	    74%
phi-2	    72%     73%
