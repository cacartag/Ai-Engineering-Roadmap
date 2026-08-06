# LLM Architectures & Decoder-Only Transformers

[&larr; Back to Dashboard](../../index.html)

## Requirements

### Read Vaswani et al. ’Attention Is All You Need’ paper
**Resource:** [https://arxiv.org/abs/1706.03762](https://arxiv.org/abs/1706.03762)

**Acceptance Criteria:**
- [ ] Read the complete paper
- [ ] Understand scaled dot-product attention formula
- [ ] Understand multi-head attention mechanism
- [ ] Understand positional encoding

**Deliverable:** Annotated paper summary with key equations

---

### Study GPT Causal Decoder architecture, RoPE embeddings, & SwiGLU
**Resource:** *(Internal / See study guide below)*

**Acceptance Criteria:**
- [ ] Explain causal (autoregressive) masking and why GPT uses it
- [ ] Understand RoPE (Rotary Position Embeddings) intuition
- [ ] Understand SwiGLU activation function
- [ ] Compare encoder-only (BERT) vs decoder-only (GPT) architectures

**Deliverable:** Architecture comparison document

---

### Understand Multi-Head Attention, Grouped-Query Attention (GQA), & KV Cache
**Resource:** *(Internal / See study guide below)*

**Acceptance Criteria:**
- [ ] Implement Multi-Head Attention from scratch in PyTorch
- [ ] Explain Grouped-Query Attention (GQA) and why it saves memory
- [ ] Explain KV Cache and how it speeds up inference
- [ ] Calculate memory requirements for different cache sizes

**Deliverable:** MHA implementation + memory analysis

---

### Mini-Project: Build a Mini-GPT model from scratch in PyTorch (nanoGPT style)
**Resource:** [https://github.com/karpathy/nanoGPT](https://github.com/karpathy/nanoGPT)

**Acceptance Criteria:**
- [ ] Build a decoder-only Transformer from scratch in PyTorch
- [ ] Implement token + positional embeddings
- [ ] Implement causal self-attention with masking
- [ ] Implement feed-forward blocks with residual connections
- [ ] Train on a text dataset and generate samples
- [ ] Model generates coherent text

**Deliverable:** Complete nanoGPT-style implementation repo

---

