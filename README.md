
---

## 🇪🇸 Assignment 3: English to Spanish Seq2Seq with BiLSTM

**Notebook**: `Aishwarya_A3_DL!!!.ipynb`

- Dataset: English–Spanish parallel corpus from [Tatoeba via ManyThings.org](http://www.manythings.org/anki/)
- Encoder: ✅ **Bidirectional LSTM**
- Decoder: Standard LSTM with teacher forcing
- Tokenization, padding, and preprocessing included
- Output: Translation predictions for Spanish sentences

### What was implemented:
- `Bidirectional(LSTM(...))` used in encoder
- Input and target vocabulary handling
- End-to-end training with `categorical_crossentropy` loss

---

## 🇫🇷 Assignment 4: French to English Seq2Seq with Attention

**Notebook**: `A4_Bhethanabotla_Aishwarya_!ipynb.ipynb`

- Dataset: [IWSLT 2017 French-English](https://huggingface.co/datasets/iwslt2017)
- Encoder: GRU
- Decoder: GRU with **Bahdanau Attention**
- Evaluation: ✅ **BLEU score**, ✅ **Perplexity**
- Outputs attention-aligned translations

---

## 📦 Installation

```bash
pip install -r requirements.txt


