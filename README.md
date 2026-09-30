# Bayan Applied NLP Course Project --bayann1pprogHYA

## Training Context (SDAIA-AIE)
- **Program Code:** SDAIA-F-CRS100-01-01
- **Academy:** SDAIA Academy ([SDAIA Academy GitHub](https://github.com/SDAIAAcademy))
- **Trainer:** Meaad Al-Sarri
- **Trainee:** Haya Albaqami
- **Models & Data Sources:** HuggingFace Hub & Bayan Course Repositories.

---

## §1. Notebooks Links (Colab)
| Notebook ID | Description | Colab Link |
| :--- | :--- | :--- |
| **Notebook 01** | Environment, Setup & Processing Pipeline | [Open in Colab](https://colab.research.google.com) |
| **Notebook 02** | Attention Mechanisms & Transformers | [Open in Colab](https://colab.research.google.com) |
| **Notebook 03** | Classification & Named Entity Recognition (NER) | [Open in Colab](https://colab.research.google.com) |
| **Notebook 04** | Question Answering & No-Answer Alignment | [Open in Colab](https://colab.research.google.com) |
| **Notebook 05** | FAISS Retrieval & Re-ranking | [Open in Colab](https://colab.research.google.com) |
| **Notebook 06** | Evaluation, Slices & Confidence Intervals | [Open in Colab](https://colab.research.google.com) |
| **Notebook 07** | Error Analysis & Top Fixes | [Open in Colab](https://colab.research.google.com) |
| **Notebook 08** | Benchmarking & Project Mode Deployment | [Open in Colab](https://colab.research.google.com) |
| **Notebook 09** | Model Serving & API Integration | [Open in Colab](https://colab.research.google.com) |

---

## §2. MEASURED_SMOKE & Results Table
The core evaluation metrics measured under smoke and project configurations:

| Metric / Task | Measured Value | Target Threshold | Evidence Reference |
| :--- | :--- | :--- | :--- |
| **Macro-F1 (Entity-1)** | 0.84 | > 0.80 | `/reports/measured_smoke_metrics.json`[cite: 1] |
| **Re-ranking MRR** | 0.89 (improved from 0.72) | Baseline improvement | `/reports/reranking_comparison.json`[cite: 1] |
| **Recall@k** | 0.94 | > 0.90 | `/reports/reranking_comparison.json`[cite: 1] |

### Reproduction Steps:
1. Clone the repository and navigate to the root folder:
   ```bash
   git clone [https://github.com/progHYA/--bayann1pprogHYA.git](https://github.com/progHYA/--bayann1pprogHYA.git)
   cd --bayann1pprogHYA
