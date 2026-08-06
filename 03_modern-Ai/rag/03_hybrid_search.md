# Hybrid Search (Sparse + Dense Retrieval)

[&larr; Back to Dashboard](../../index.html)

## Requirements

### Study BM25 Lexical Keyword Search algorithm & Sparse Vectors
**Resource:** *(Internal / See study guide below)*

**Acceptance Criteria:**
- [ ] Implement BM25 scoring algorithm conceptually
- [ ] Understand TF-IDF vs BM25 differences
- [ ] Implement sparse vector representation
- [ ] Compare lexical vs semantic search results on same queries

**Deliverable:** BM25 implementation + comparison notebook

---

### Master Reciprocal Rank Fusion (RRF) for merging Sparse + Dense results
**Resource:** *(Internal / See study guide below)*

**Acceptance Criteria:**
- [ ] Implement Reciprocal Rank Fusion algorithm
- [ ] Merge ranked lists from sparse + dense retrievers
- [ ] Tune the RRF k parameter
- [ ] Compare fused results to individual retrievers

**Deliverable:** RRF implementation with evaluation

---

### Practice Qdrant / Pinecone Hybrid Search APIs
**Resource:** *(Internal / See study guide below)*

**Acceptance Criteria:**
- [ ] Use Qdrant or Pinecone hybrid search API
- [ ] Configure sparse + dense vectors
- [ ] Run hybrid queries with different alpha weights
- [ ] Evaluate hybrid vs pure dense retrieval

**Deliverable:** Hybrid search API usage notebook

---

### Mini-Project: Implement a Hybrid RAG Search Engine with BM25 + Vector Retrieval
**Resource:** *(Internal / See study guide below)*

**Acceptance Criteria:**
- [ ] Combine BM25 + vector retrieval in a RAG pipeline
- [ ] Implement RRF fusion of results
- [ ] Connect to LLM for answer generation
- [ ] Evaluate answer quality with and without hybrid search
- [ ] Show improvement over dense-only retrieval

**Deliverable:** Hybrid RAG pipeline with evaluation

---

