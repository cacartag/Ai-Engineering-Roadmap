# Chain-of-Thought & Tree-of-Thought Reasoning

[&larr; Back to Dashboard](../../index.html)

## Requirements

### Read Wei et al. ’Chain-of-Thought’ and Yao et al. ’Tree of Thoughts’ papers
**Resource:** [https://arxiv.org/abs/2201.11903](https://arxiv.org/abs/2201.11903)

**Acceptance Criteria:**
- [ ] Read Chain-of-Thought paper
- [ ] Read Tree of Thoughts paper (arXiv:2305.10601)
- [ ] Understand when CoT improves performance
- [ ] Understand ToT's search over reasoning paths

**Deliverable:** Both paper summaries

---

### Implement Self-Consistency decoding (sampling multiple CoT paths & voting)
**Resource:** *(Internal / See study guide below)*

**Acceptance Criteria:**
- [ ] Implement Self-Consistency: sample N CoT paths
- [ ] Extract final answers from each path
- [ ] Take majority vote as final answer
- [ ] Show improvement over single CoT on math problems

**Deliverable:** Self-Consistency implementation with evaluation

---

### Implement Tree-of-Thought (ToT) search over candidate reasoning steps
**Resource:** *(Internal / See study guide below)*

**Acceptance Criteria:**
- [ ] Implement ToT with BFS or DFS search strategy
- [ ] Generate candidate next steps at each node
- [ ] Evaluate candidates with LLM scoring
- [ ] Prune low-quality branches
- [ ] Track and return best reasoning path

**Deliverable:** ToT search implementation

---

### Mini-Project: Build a CoT / ToT solver script for complex math word problems
**Resource:** *(Internal / See study guide below)*

**Acceptance Criteria:**
- [ ] Solver handles math word problems (GSM8K-style)
- [ ] Uses CoT prompting with step-by-step reasoning
- [ ] Implements Self-Consistency for improved accuracy
- [ ] Optionally uses ToT for harder problems
- [ ] Evaluates accuracy on 20+ test problems

**Deliverable:** Math reasoning solver with CoT/ToT + evaluation

---

