
#  Speech Understanding Assignment 3

This repository contains the complete solution to **Assignment 3** of CSL7770 (Speech Understanding), AY 2024–25, IIT Jodhpur.

---

##  Contents

- `report.pdf` – Paper review + Bonus task write-up
- `SpeechGLUE_Bonus_Workflow.ipynb` – Colab notebook for reproduction, DoRA training, and evaluation
- Feature extraction using Wav2Vec2
- DoRA-based training on SNIPS
- Transfer evaluation on SST-2 and MRPC
- Final evaluation and metrics

---

##  Paper Reviewed

**Title:** SpeechGLUE: How Well Can Self-Supervised Speech Models Capture Linguistic Knowledge?  
**Venue:** Interspeech 2023

---

##  Project Structure

```
.
├── report.pdf
├── SpeechGLUE_Bonus_Workflow.ipynb
└── README.md
```

---

##  How to Reproduce (Colab)

>  All steps run on CPU — GPU optional but recommended.

1. Run the notebook `SpeechGLUE_Bonus_Workflow.ipynb` in Colab.
2. It will:
   - Convert text to audio (gTTS)
   - Extract features using Wav2Vec2
   - Train DoRA model on SNIPS
   - Attach new heads for SST-2 and MRPC
   - Print accuracy + classification reports

---

##  Results

| Dataset   | Accuracy |
|-----------|----------|
| SNIPS (DoRA fine-tuned) | 35.5% |
| SST-2 (transfer)        | 54.6% |
| MRPC (transfer)         | 69.2% |

---

##  Author

**Name:** Jyotishman Das  
**Roll No.:** M24CSA013  
**Course:** CSL7770: Speech Understanding  
**Instructor:** Prof. Richa Singh

---
