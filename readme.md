# HateQwen: A Novel Approach for Hate Speech Detection

## Introduction
HateQwen is an advanced hate speech detection model built on the **Qwen2-1.5** architecture and fine-tuned using **Low-Rank Adaptation (LoRA)**. By leveraging the **dynaHate** dataset, HateQwen achieves significant improvements in accuracy and F1 score, outperforming prominent models like **TinyLLaMA, OPT-1.3B, and phi-2**.

## Key Features
- **Model:** Qwen2-1.5, fine-tuned using LoRA.
- **Dataset:** dynaHate – a comprehensive dataset for hate speech detection.
- **Performance:**
  - **Accuracy:** 84%
  - **F1 Score:** 85%
- **Benchmarking:** Outperforms models like TinyLLaMA, OPT-1.3B, and phi-2 in hate speech detection.

## Installation
### Prerequisites
Ensure you have the following dependencies installed:
```bash
pip install torch transformers
```

### Running the Model
Clone the repository and run the model:
```bash
git clone 
cd HateQwen
python run_model.py
```

## Performance Evaluation
HateQwen was tested on the dynaHate dataset, achieving:
- **Accuracy:** 84%
- **F1 Score:** 85%

### Model Comparison
| Model       | Accuracy | F1 Score |
|------------|----------|----------|
| **HateQwen** | **84%**  | **85%**  |
| TinyLLaMA   | 71%      | 72%      |
| OPT-1.3B    | 73%      | 74%      |
| phi-2       | 72%      | 73%      |

## License
This project is licensed under the **MIT License**.

---

⭐ **Star this repository if you find it useful!**

