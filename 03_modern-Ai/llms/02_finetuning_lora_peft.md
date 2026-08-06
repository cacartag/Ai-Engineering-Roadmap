# Fine-Tuning & Parameter-Efficient Fine-Tuning (LoRA/PEFT)

[&larr; Back to Dashboard](../../index.html)

## Requirements

### Study LoRA (Low-Rank Adaptation) and QLoRA research papers
**Resource:** [https://arxiv.org/abs/2106.09685](https://arxiv.org/abs/2106.09685)

**Acceptance Criteria:**
- [ ] Read LoRA paper and understand low-rank decomposition
- [ ] Read QLoRA paper and understand 4-bit quantized training
- [ ] Understand why PEFT is needed (full fine-tuning cost)

**Deliverable:** Paper summaries with key insights

---

### Complete Hugging Face TRL library documentation
**Resource:** [https://huggingface.co/docs/trl](https://huggingface.co/docs/trl)

**Acceptance Criteria:**
- [ ] Read TRL documentation for SFTTrainer
- [ ] Understand the TRL training pipeline
- [ ] Know how to configure LoRA adapters with PEFT

**Deliverable:** TRL configuration reference notes

---

### Master Supervised Fine-Tuning (SFT) & Alpaca dataset formatting
**Resource:** *(Internal / See study guide below)*

**Acceptance Criteria:**
- [ ] Format a dataset in Alpaca instruction format
- [ ] Understand chat templates (ChatML, Llama format)
- [ ] Create train/test split for SFT dataset
- [ ] Know the difference between SFT, DPO, and RLHF

**Deliverable:** Formatted SFT dataset + format comparison notes

---

### Mini-Project: Fine-tune Llama 3 or Mistral 7B using QLoRA & Unsloth on GPU
**Resource:** *(Internal / See study guide below)*

**Acceptance Criteria:**
- [ ] Fine-tune a 7B+ model using QLoRA (4-bit quantization)
- [ ] Use Unsloth or PEFT + BitsAndBytes for efficiency
- [ ] Train for at least 1 epoch on custom instruction dataset
- [ ] Evaluate before and after fine-tuning
- [ ] Save and load LoRA adapter weights

**Deliverable:** Fine-tuning notebook + saved adapter weights

---

