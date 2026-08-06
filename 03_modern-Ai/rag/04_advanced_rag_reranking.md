# Advanced RAG: Re-ranking, Query Transformation & GraphRAG

[&larr; Back to Dashboard](../../index.html)

## Requirements

### Study Cohere Rerank / BGE Cross-Encoders and HyDE (Hypothetical Embeddings)
**Resource:** [https://docs.cohere.com/docs/reranking](https://docs.cohere.com/docs/reranking)

**Acceptance Criteria:**
- [ ] Use Cohere Rerank API on retrieved documents
- [ ] Implement cross-encoder reranking with BGE
- [ ] Understand HyDE (generate hypothetical document, then search)
- [ ] Compare retrieval quality with and without reranking

**Deliverable:** Reranking implementation + HyDE notebook

---

### Read GraphRAG paper & Query Transformation techniques (Multi-Query, Step-Back)
**Resource:** [https://arxiv.org/abs/2404.16130](https://arxiv.org/abs/2404.16130)

**Acceptance Criteria:**
- [ ] Read GraphRAG paper
- [ ] Understand query transformation techniques
- [ ] Implement Multi-Query: generate multiple queries from one
- [ ] Implement Step-Back prompting for complex queries

**Deliverable:** Paper notes + query transformation implementations

---

### Implement Context Compression and Self-RAG verification loops
**Resource:** *(Internal / See study guide below)*

**Acceptance Criteria:**
- [ ] Implement context compression (reduce retrieved docs to key info)
- [ ] Implement Self-RAG verification loop
- [ ] Agent decides whether retrieval is needed
- [ ] Agent verifies answer against retrieved context

**Deliverable:** Self-RAG + context compression implementation

---

### Mini-Project: Build an Advanced RAG Pipeline with Query Rewriting + Re-ranking
**Resource:** *(Internal / See study guide below)*

**Acceptance Criteria:**
- [ ] Pipeline includes query rewriting step
- [ ] Pipeline includes retrieval + reranking step
- [ ] Pipeline includes answer generation with citations
- [ ] Evaluate end-to-end pipeline quality
- [ ] Compare to baseline RAG without advanced features

**Deliverable:** Advanced RAG pipeline with evaluation

---

