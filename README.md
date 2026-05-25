<img src="https://capsule-render.vercel.app/api?type=rect&color=0c0c0a&height=2&section=header"/>

<br>

<table width="100%" border="0" cellspacing="0" cellpadding="0">
<tr>
<td valign="bottom" width="65%">
<sup>AI SYSTEMS LAB &nbsp;·&nbsp; BENGALURU, INDIA</sup>

# Shivashant <br> *Manohar*

<sub><i>Building reliable AI systems through verifier-guided evaluation and alignment.</i></sub>
</td>
<td valign="bottom" align="right" width="35%">
<sub>
<a href="https://hey-shiv.github.io">lab ↗</a><br>
<a href="https://huggingface.co/hey-shiv">huggingface ↗</a><br>
<a href="https://medium.com/@shivashant.personal">medium ↗</a><br>
<a href="https://x.com/NaadhLabs">x / @NaadhLabs ↗</a><br>
<a href="https://linkedin.com/in/shivashant">linkedin ↗</a>
</sub>
</td>
</tr>
</table>

---

**I** build verifier-guided AI systems focused on reliability, evaluation infrastructure, and post-training workflows. The work is deliberately systems-oriented — structured traces, deterministic verifiers, preference data, reward modeling, reranking loops, held-out evaluations, and observability surfaces that make failures inspectable. Currently exploring research engineering and AI systems opportunities.

<br>

---

<sup>01 &nbsp;—&nbsp; FLAGSHIP SYSTEMS</sup>

<br>

<table width="100%" border="0">
<tr>
<td valign="top" width="75%">

### AgentAlign Lab
<sup>Terminal agents &nbsp;·&nbsp; Active / Post-training</sup>

Verifier-guided preference learning pipeline for reliable terminal agents — structured trajectories, deterministic verifiers, DPO preference optimization, held-out evaluations, and failure analysis.

```
Task Suite  →  Trajectories  →  Preference Pairs  →  DPO Eval
schemas + verifiers · actions + evidence · chosen/rejected · held-out
```

<sub>`task suite` `trajectory logs` `verifier-ranked pairs` `DPO/LoRA` `held-out evals`</sub>

</td>
<td valign="top" align="right" width="25%">
<br>
<sub>● Active</sub><br><br>
<sub><a href="https://hey-shiv.github.io/projects/agentalign-lab/">Project detail ↗</a></sub><br>
<sub><a href="https://hey-shiv.github.io/blogs/AgentAlign%20Lab/">Research posts ↗</a></sub>
</td>
</tr>
</table>

<table width="100%" border="0">
<tr>
<td valign="top" width="75%">

### SvaraAlign Lab
<sup>Generative music &nbsp;·&nbsp; Active / Alignment</sup>

Verifier-guided alignment for raga-faithful AI music generation — symbolic verification, expert preference learning, reward modeling, reranking systems, and culturally grounded evaluation loops.

```
Raga Task  →  SvaraJudge  →  SvaraPrefs  →  SvaraReward  →  Rerank + Eval
prompt + tonic · JSON evidence · expert pairs · reward model · held-out
```

<sub>`SvaraJudge` `SvaraTrace` `SvaraPrefs` `SvaraReward` `reranking` `held-out evals`</sub>

</td>
<td valign="top" align="right" width="25%">
<br>
<sub>● Active</sub><br><br>
<sub><a href="https://hey-shiv.github.io/projects/svaraalign-lab/">Project detail ↗</a></sub>
</td>
</tr>
</table>

---

<sup>02 &nbsp;—&nbsp; FOCUS</sup>

<br>

<table width="100%">
<tr>
<td valign="top" width="50%">

<sub>INFRASTRUCTURE</sub>

- Verifier-guided systems
- Preference learning & DPO pipelines
- Evaluation & observability
- Reward modeling & structured traces
- Post-training systems

</td>
<td valign="top" width="50%">

<sub>RESEARCH</sub>

- AI reliability engineering
- Culturally grounded generative AI
- Raga-faithful music alignment
- Human feedback systems
- Failure analysis & postmortems

</td>
</tr>
</table>

---

<sup>03 &nbsp;—&nbsp; PHILOSOPHY</sup>

<br>

| | | |
|:--|:--:|:--|
| *Evaluation integrity* | › | benchmark theater |
| *Reproducibility* | › | flashy demos |
| *Verifier quality* | = | ceiling for alignment quality |
| *Observable systems* | › | black-box pipelines |
| *Honest failure analysis* | › | cherry-picked results |

---

<sup>04 &nbsp;—&nbsp; FAILURE NOTES</sup>

<br>

- **Verifier instability** &nbsp;—&nbsp; When the judge changes under identical inputs, training data becomes noisy.
- **Trajectory schema redesigns** &nbsp;—&nbsp; Missing trace fields make downstream preference comparisons hard to audit.
- **Reward leakage** &nbsp;—&nbsp; Models can learn the verifier shortcut instead of the intended behavior.
- **Tonic mismatch** &nbsp;—&nbsp; Raga-faithful generation fails quickly when pitch context is underspecified.
- **Evaluation integrity** &nbsp;—&nbsp; Held-out tasks and blind checks matter when the system starts optimizing.

---

<sup>05 &nbsp;—&nbsp; WRITING</sup>

<br>

<table width="100%">
<tr>
<td><i><a href="https://hey-shiv.github.io/blogs/AgentAlign%20Lab/day-1-core-execution-pipeline.html">Day 1 — Core Execution Pipeline for Verifier-Guided Terminal Agents</a></i></td>
<td align="right"><sub>May 23, 2026 &nbsp;·&nbsp; AgentAlign Lab</sub></td>
</tr>
<tr>
<td><sub><i>Planned: trace schemas · reward leakage · raga verifier drift</i></sub></td>
<td align="right"><sub>upcoming</sub></td>
</tr>
</table>

---

<sup>06 &nbsp;—&nbsp; PREVIOUS WORK</sup>

<br>

***Mini Modern LLM*** &nbsp;—&nbsp; Decoder-only transformer from scratch. Byte-level BPE tokenization, memmap data loading, RoPE, GQA, RMSNorm, SwiGLU, CLI inference, and a Gradio interface.

***Context-Aware Federated IDS*** &nbsp;—&nbsp; Privacy-preserving intrusion detection for decentralized smart healthcare using federated learning and lightweight aggregation.

<br>

---

<table width="100%">
<tr>
<td><sub>Bengaluru, India &nbsp;·&nbsp; shivashant.work@gmail.com</sub></td>
<td align="right"><sub><i>verifier quality sets the ceiling for alignment quality</i></sub></td>
</tr>
</table>
