# Deep Q-Networks (DQN)

[&larr; Back to Dashboard](../../index.html)

## Requirements

### Read DeepMind’s Playing Atari with Deep RL paper
**Resource:** [https://arxiv.org/abs/1312.5602](https://arxiv.org/abs/1312.5602)

**Acceptance Criteria:**
- [ ] Read the complete paper
- [ ] Understand why neural networks approximate Q-values
- [ ] Understand experience replay and why it's needed
- [ ] Understand target network and why it stabilizes training

**Deliverable:** Paper summary with key innovations noted

---

### Master Deep Q-Networks (DQN), Replay Buffers, & Target Networks
**Resource:** *(Internal / See study guide below)*

**Acceptance Criteria:**
- [ ] Implement neural network Q-function approximator
- [ ] Implement Experience Replay Buffer with sampling
- [ ] Implement Target Network with periodic copying
- [ ] Understand how these 3 components work together

**Deliverable:** DQN components implemented in PyTorch

---

### Study Double DQN & Dueling DQN improvements
**Resource:** *(Internal / See study guide below)*

**Acceptance Criteria:**
- [ ] Explain Double DQN and how it reduces overestimation
- [ ] Explain Dueling DQN architecture (V + A streams)
- [ ] Implement at least one improvement on top of vanilla DQN

**Deliverable:** Notes + improved DQN implementation

---

### Mini-Project: Build a PyTorch DQN agent to solve Gym CartPole-v1
**Resource:** *(Internal / See study guide below)*

**Acceptance Criteria:**
- [ ] DQN agent solves CartPole-v1 (500 reward)
- [ ] Uses experience replay and target network
- [ ] Plots reward per episode over training
- [ ] Training converges within 500 episodes
- [ ] Can render and watch the trained agent

**Deliverable:** PyTorch DQN agent + training visualization

---

