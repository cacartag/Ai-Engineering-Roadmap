# Document Chunking Strategies & Embedding Models

[&larr; Back to Dashboard](../../index.html)

## Requirements

### Study Document Chunking strategies (Fixed-size, Recursive, Semantic)
**Resource:** *(Internal / See study guide below)*

**Acceptance Criteria:**
- [ ] Implement fixed-size chunking with overlap
- [ ] Implement recursive character-based chunking
- [ ] Implement semantic chunking (by sentence similarity)
- [ ] Compare chunk quality across strategies

**Deliverable:** 3 chunking strategy implementations

---

### Benchmark Sentence-Transformers (BGE, E5, OpenAI text-embedding-3)
**Resource:** [https://www.sbert.net/](https://www.sbert.net/)

**Acceptance Criteria:**
- [ ] Benchmark BGE, E5, and OpenAI embedding models
- [ ] Compare embedding dimensions and speed
- [ ] Evaluate retrieval quality on same test queries
- [ ] Measure inference latency per document

**Deliverable:** Embedding model benchmark notebook

---

### Measure retrieval recall and precision across chunk sizes
**Resource:** *(Internal / See study guide below)*

**Acceptance Criteria:**
- [ ] Create a test dataset with known relevant documents
- [ ] Measure retrieval recall at different k values
- [ ] Measure retrieval precision at different k values
- [ ] Test across different chunk sizes (256, 512, 1024 tokens)

**Deliverable:** Retrieval evaluation notebook

---

### Mini-Project: Build an automated Chunking & Embedding Pipeline for PDFs
**Resource:** *(Internal / See study guide below)*

**Acceptance Criteria:**
- [ ] Accept PDF files as input
- [ ] Extract text with PyPDF2 or pdfplumber
- [ ] Chunk extracted text using chosen strategy
- [ ] Generate embeddings for all chunks
- [ ] Store in vector database
- [ ] Verify with test queries

**Deliverable:** PDF → chunks → embeddings → vector DB pipeline

---

