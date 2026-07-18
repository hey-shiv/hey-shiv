<div align="center">
<br>

<sub><kbd>Public AI systems lab</kbd> &nbsp; <kbd>Verifier-guided</kbd> &nbsp; <kbd>Post-training</kbd></sub>

<br><br>

# Shivashant Manohar

### Building reliable AI systems through verifier-guided evaluation and alignment.

<sup>AI Systems · Post-Training · Evals · Alignment · Observability</sup>

<br>

<a href="https://hey-shiv.github.io"><kbd>lab ↗</kbd></a> &nbsp;
<a href="https://github.com/hey-shiv"><kbd>github ↗</kbd></a> &nbsp;
<a href="https://huggingface.co/hey-shiv"><kbd>huggingface ↗</kbd></a> &nbsp;
<a href="https://medium.com/@shivashant.personal"><kbd>medium ↗</kbd></a> &nbsp;
<a href="https://x.com/NaadhLabs"><kbd>x ↗</kbd></a> &nbsp;
<a href="https://linkedin.com/in/shivashant"><kbd>linkedin ↗</kbd></a>

<br><br>

</div>

I build verifier-guided AI systems focused on reliability, evaluation infrastructure, and post-training workflows. Current work centers on AgentAlign Lab. Currently exploring research engineering and AI systems opportunities.

<br>

---

<sup>CURRENT WORK / LABS — FLAGSHIP SYSTEMS</sup>

<br>

**AgentAlign Lab** &nbsp; <sup>`terminal agents`</sup> &nbsp; <sup>`Active / Post-training`</sup>

Verifier-guided preference learning pipeline for reliable terminal agents — structured trajectories, deterministic verifiers, DPO preference optimization, held-out evaluations, and failure analysis.

```
Task Suite    →    Trajectories    →    Preference Pairs    →    DPO Eval
schemas + verifiers  actions + evidence    chosen / rejected     held-out comparison
```

<sub>`task suite` `trajectory logs` `verifier-ranked pairs` `DPO/LoRA` `held-out evals`</sub>

<sub>Systems focus: AI reliability · agent tooling · post-training infrastructure · evaluation integrity</sub>

→ [Project detail](https://hey-shiv.github.io/projects/agentalign-lab/) &nbsp; · &nbsp; [Research posts](https://hey-shiv.github.io/blogs/AgentAlign%20Lab/)

<br>


---

<sup>ABOUT / LAB PREMISE</sup>

## Verifier quality shapes model behavior.

I am interested in AI systems where evaluation is not a reporting layer after the fact, but a design constraint that shapes training data, reward signals, failure analysis, and deployment behavior.

<br>

<table>
<tr>
<td valign="top" width="50%">
<sub><b>CURRENT FOCUS</b></sub><br><br>

- Verifier-guided AI systems
- Preference learning and DPO pipelines
- Evaluation and observability systems
- Reward modeling and structured traces
- AI systems architecture and reliability engineering

</td>
<td valign="top" width="50%">
<sub><b>SYSTEMS INTERESTS</b></sub><br><br>

- AI reliability engineering
- Evaluation infrastructure
- Post-training systems
- Reward modeling & preference optimization
- Structured traces and observability

</td>
</tr>
</table>

<br>

---

<sup>ENGINEERING PHILOSOPHY</sup>

<br>

| | |
|---|---|
| Evaluation integrity | › benchmark theater |
| Reproducibility | › flashy demos |
| Verifier quality | = ceiling for alignment quality |
| Observable systems | › black-box pipelines |
| Honest failure analysis | › cherry-picked results |

<br>

---

<sup>FAILURE ANALYSIS / LAB NOTES — PROBLEMS WORTH MAKING VISIBLE</sup>

<br>

- **Verifier instability** — When the judge changes under identical inputs, training data becomes noisy.
- **Trajectory schema redesigns** — Missing trace fields make downstream preference comparisons hard to audit.
- **Reward leakage** — Models can learn the verifier shortcut instead of the intended behavior.
- **Evaluation integrity** — Held-out tasks and blind checks matter when the system starts optimizing.

<br>

---

<sup>WRITING / SYSTEMS ESSAYS — SYSTEMS NOTES WRITTEN CLOSE TO THE WORK</sup>

<br>

- [Day 1 — Core Execution Pipeline for Verifier-Guided Terminal Agents](https://hey-shiv.github.io/blogs/AgentAlign%20Lab/day-1-core-execution-pipeline.html) &nbsp; <sup>May 23, 2026 / AgentAlign Lab</sup>
- *Planned: trace schemas and reward leakage* &nbsp; <sup>upcoming</sup>

<br>

---

<sup>PREVIOUS WORK</sup>

<br>

**Mini Modern LLM** — Decoder-only transformer built from scratch with byte-level BPE tokenization, memmap data loading, RoPE, GQA, RMSNorm, SwiGLU, CLI inference, and a Gradio interface.

**Context-Aware Federated Intrusion Detection** — Privacy-preserving intrusion detection system using federated learning and lightweight aggregation for decentralized smart healthcare networks.

<br>

---

<div align="center">
<sub>Bengaluru, India &nbsp;/&nbsp; shivashant.work@gmail.com</sub>
</div>
