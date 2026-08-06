# Quantization, GGUF & Running Local Models with Ollama

[&larr; Back to Dashboard](../../index.html)

## Requirements

### Study GGUF format, AWQ, and GPTQ quantization papers
**Resource:** *(Internal / See study guide below)*

**Acceptance Criteria:**
- [ ] Explain GGUF format and its advantages
- [ ] Explain AWQ quantization and how it preserves quality
- [ ] Explain GPTQ quantization method
- [ ] Compare 4-bit vs 8-bit vs 16-bit quality tradeoffs

**Deliverable:** Quantization comparison document

---

### Master Ollama CLI, Modelfiles, and local vLLM API server execution
**Resource:** [https://ollama.com/](https://ollama.com/)

**Acceptance Criteria:**
- [ ] Install Ollama and pull a model
- [ ] Create a custom Modelfile with system prompt
- [ ] Run local vLLM API server
- [ ] Make API calls to local model endpoint

**Deliverable:** Working local model setup + custom Modelfile

---

### Benchmark latency, throughput (tokens/sec), & memory footprint
**Resource:** *(Internal / See study guide below)*

**Acceptance Criteria:**
- [ ] Benchmark tokens/second for different quantization levels
- [ ] Measure memory footprint for each quantization
- [ ] Compare output quality across quantizations on same prompts
- [ ] Create a benchmark results table

**Deliverable:** Benchmark results with comparison table

---

### Mini-Project: Deploy a local quantized Llama 3 model with Ollama & API backend
**Resource:** *(Internal / See study guide below)*

**Acceptance Criteria:**
- [ ] Deploy a quantized model locally with Ollama
- [ ] Create an API backend (FastAPI or Flask) that calls the model
- [ ] API accepts prompts and returns completions
- [ ] Include streaming response support
- [ ] Document setup and usage instructions

**Deliverable:** Deployed local model with API + README

---

