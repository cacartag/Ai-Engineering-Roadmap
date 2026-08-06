# ReAct Pattern & Tool-Use Execution

[&larr; Back to Dashboard](../../index.html)

## Requirements

### Read Yao et al. ’ReAct: Synergizing Reasoning and Acting in LLMs’
**Resource:** [https://arxiv.org/abs/2210.03629](https://arxiv.org/abs/2210.03629)

**Acceptance Criteria:**
- [ ] Read the complete ReAct paper
- [ ] Understand Thought-Action-Observation pattern
- [ ] Compare to Chain-of-Thought and Act-only baselines

**Deliverable:** Paper summary

---

### Master OpenAI Function Calling & JSON Schema tool definition
**Resource:** [https://platform.openai.com/docs/guides/function-calling](https://platform.openai.com/docs/guides/function-calling)

**Acceptance Criteria:**
- [ ] Read OpenAI Function Calling documentation
- [ ] Define tool schemas in JSON format
- [ ] Handle function call responses in code
- [ ] Implement parallel function calling

**Deliverable:** Working function calling examples

---

### Implement Thought-Action-Observation loop execution parser
**Resource:** *(Internal / See study guide below)*

**Acceptance Criteria:**
- [ ] Implement the Thought-Action-Observation loop
- [ ] Parse LLM output to extract action and action input
- [ ] Execute the action and return observation to LLM
- [ ] Handle errors and invalid actions gracefully

**Deliverable:** ReAct loop implementation

---

### Mini-Project: Build a Python ReAct Agent with Web Search & Calculator tools
**Resource:** *(Internal / See study guide below)*

**Acceptance Criteria:**
- [ ] Agent has at least 2 tools (web search + calculator minimum)
- [ ] Uses ReAct pattern with explicit reasoning
- [ ] Can answer multi-step questions requiring tool use
- [ ] Handles tool errors gracefully
- [ ] Logs full Thought-Action-Observation traces

**Deliverable:** ReAct agent with tools + trace logs

---

