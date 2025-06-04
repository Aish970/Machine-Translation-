
---

## 📘 Assignment 3: N-Gram Based Translation

**File**: `Aishwarya_A3_DL!!!.ipynb`  
**Approach**:  
- Uses unigram and bigram frequency statistics for translation
- Implements **Good-Turing** and **Kneser-Ney** smoothing
- Predicts English output word-by-word given French context
- Evaluates using **perplexity**

**Key Components**:
- Bigram language model
- Frequency-based predictions
- Probability smoothing for unseen words
- Perplexity metric for model evaluation

---

## 🤖 Assignment 4: Neural Machine Translation with Seq2Seq

**File**: `A4_Bhethanabotla_Aishwarya_!ipynb.ipynb`  
**Approach**:  
- Trains an **encoder-decoder** model with **GRU** and **Bahdanau attention**
- Uses the [IWSLT 2017 French-English](https://huggingface.co/datasets/iwslt2017) dataset
- Evaluates with **BLEU Score** and **perplexity**

**Key Components**:
- Tokenization and padding
- Encoder-Decoder architecture
- Attention mechanism for alignment
- Training with cross-entropy loss
- BLEU score-based evaluation

---

## 📊 Metrics Comparison

| Metric | N-Gram Model | Seq2Seq Model |
|--------|--------------|---------------|
| Perplexity | ✅ Implemented | ✅ Implemented |
| BLEU Score | ❌ Not applicable | ✅ Implemented |
| Qualitative Translation | ✅ Rule-based | ✅ Learned end-to-end |

---

## ⚙️ Installation

Install required libraries:

```bash
pip install -r requirements.txt

