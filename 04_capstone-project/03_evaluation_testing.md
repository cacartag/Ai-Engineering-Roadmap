# Evaluation & Testing Suite Execution

[&larr; Back to Dashboard](../index.html)

## Requirements

### Build a test dataset of 30+ representative test queries & ground truth answers
**Resource:** *(Internal / See study guide below)*

**Acceptance Criteria:**
- [ ] Create 30+ diverse test queries
- [ ] Include easy, medium, and hard questions
- [ ] Provide ground truth answers for each
- [ ] Include edge cases and adversarial inputs

**Deliverable:** Test dataset JSON/CSV file

---

### Execute automated evaluation metrics (Faithfulness, Answer Relevance, Latency)
**Resource:** *(Internal / See study guide below)*

**Acceptance Criteria:**
- [ ] Run automated metrics (Faithfulness, Relevance, Correctness)
- [ ] Measure latency per request
- [ ] Measure token usage and cost
- [ ] Generate results in structured format

**Deliverable:** Automated evaluation results

---

### Generate an Evaluation Report documenting accuracy & benchmark performance
**Resource:** *(Internal / See study guide below)*

**Acceptance Criteria:**
- [ ] Document includes accuracy by category
- [ ] Documents latency benchmarks
- [ ] Compares to baseline/target metrics
- [ ] Highlights strengths and weaknesses

**Deliverable:** Formatted evaluation report markdown

---

### Fix edge-case failures & optimize prompt/RAG parameters based on eval results
**Resource:** *(Internal / See study guide below)*

**Acceptance Criteria:**
- [ ] Identify and fix top 5 failure cases
- [ ] Optimize prompts based on evaluation results
- [ ] Tune RAG parameters (chunk size, top-k, etc.)
- [ ] Show measurable improvement after optimization

**Deliverable:** Before/after optimization comparison

---

