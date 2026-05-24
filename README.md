<div align="center">
  <h1>Mini GPT from Scratch</h1>
  <h3>A complete decoder-only Transformer language model implemented from first principles</h3>
  <p><strong>No high-level libraries. Pure PyTorch.</strong></p>
</div>

---

**Built a fully functional GPT-style LLM from scratch** to deeply understand the internals of modern language models (multi-head self-attention, causal masking, positional encodings, autoregressive decoding, etc.).

### ✨ Key Features
- Complete Transformer architecture implemented **from first principles**
- Multi-head self-attention with causal masking
- Trainable positional embeddings
- Full training pipeline with next-token prediction
- Trained end-to-end on *The Wizard of Oz* corpus
- Working inference / text generation

### 📊 Results
Successfully trained the model and validated a working training loop with converging next-token prediction loss.

### 🛠️ Tech Stack
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

### 📁 Project Structure
- `minorGPT.ipynb` → Main implementation + training + generation
- `wizard_of_oz.txt` → Training corpus

### 🚀 How to Run
```bash
git clone https://github.com/NajeebAhmad00/Mini-GPT-from-Scratch.git
cd Mini-GPT-from-Scratch
# Open minorGPT.ipynb in Jupyter / VS Code
```

🔍 What I Learned
This project gave me intimate knowledge of how GPT models actually work under the hood — knowledge I now apply in production fine-tuning and research work.
