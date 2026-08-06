# CI/CD Pipelines for AI Applications

[&larr; Back to Dashboard](../../index.html)

## Requirements

### Study GitHub Actions CI/CD workflows for AI repositories
**Resource:** [https://docs.github.com/en/actions](https://docs.github.com/en/actions)

**Acceptance Criteria:**
- [ ] Read GitHub Actions documentation
- [ ] Understand workflow syntax, triggers, jobs, steps
- [ ] Create a basic CI workflow for a Python repo

**Deliverable:** Basic GitHub Actions workflow file

---

### Implement automated prompt evaluation regression tests in CI
**Resource:** *(Internal / See study guide below)*

**Acceptance Criteria:**
- [ ] Write prompt evaluation test cases
- [ ] Compare LLM outputs against expected results
- [ ] Implement regression detection (alert on quality drops)
- [ ] Run tests in CI pipeline

**Deliverable:** Prompt evaluation test suite

---

### Automate model testing, linting (ruff), and deployment triggers
**Resource:** *(Internal / See study guide below)*

**Acceptance Criteria:**
- [ ] Add ruff linting to CI pipeline
- [ ] Add pytest for unit tests
- [ ] Implement automatic deployment on main branch merge
- [ ] Configure test matrix for different Python versions

**Deliverable:** CI/CD workflow with linting + testing + deploy

---

### Mini-Project: Build a GitHub Action workflow that runs RAG evaluation tests on PRs
**Resource:** *(Internal / See study guide below)*

**Acceptance Criteria:**
- [ ] GitHub Action triggers on PR creation
- [ ] Runs RAG evaluation tests against test queries
- [ ] Posts evaluation results as PR comment
- [ ] Blocks merge if quality drops below threshold
- [ ] Includes pass/fail status check

**Deliverable:** GitHub Action workflow file + evaluation script

---

