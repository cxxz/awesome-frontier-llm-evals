## Frontier LLM Evaluations

This repository tracks emerging, challenging and frontier evaluation tasks for foundation models including LLMs and VLMs. Many existing benchmarks are saturating as model capabilities improve; our focus is on scenarios where top‑tier models still struggle, typically achieving less than 60% success. We include open‑source benchmarks, research platforms, and challenging datasets that probe reasoning, planning and real‑world task execution. Obsolete projects and saturated benchmarks are periodically pruned so that this list stays aligned with the frontier.

## Principles

* **Frontier difficulty**: we highlight tasks where leading models consistently score well below 60% accuracy or success, exposing current limitations.
* **Realism and diversity**: the benchmarks encompass long‑context reasoning, multimodal puzzles, remote work projects, systems research tasks and economically valuable occupations.
* **Open evaluation**: each resource provides transparent evaluation protocols, verifiable solutions or human‑graded scoring, enabling reproducibility and fair comparison.

## Frontier Benchmarks & Platforms

### **Frontier-CS**
🔗 https://github.com/FrontierCS/Frontier-CS  

An **unsolved, open-ended benchmark for computer science research and algorithmic problems**.

- Problems are **genuinely difficult**, often without known optimal solutions
- Includes **research-level systems challenges** and **unbounded algorithmic optimization**
- Continuous, verifiable scoring instead of binary pass/fail
- Explicitly designed to avoid benchmark saturation  

> Models that perform well on traditional coding benchmarks still struggle significantly on Frontier-CS.

### **ADRS – AI-Driven Research for Systems**
🔗 https://github.com/UCB-ADRS/ADRS  

Evaluates AI agents on **real systems research tasks** including the following sub-domains:
  - Scheduling and load balancing
  - MoE expert placement
  - Transaction scheduling
  - LLM-SQL optimization
- Uses **reliable, executable verifiers** rather than subjective grading

### **Remote Labor Index (RLI)**
🔗 https://www.remotelabor.ai  

A benchmark measuring **end-to-end automation of real remote work** with tasks drawn from real freelance projects:
  - Game development
  - Product design
  - Data analysis
  - Architecture and media production
- Projects cost up to **$10k+** and require **100+ hours** for humans
- Best frontier agents achieve **~2.5% automation rate**

### **GDPval (OpenAI)**
🔗 https://openai.com/index/gdpval/  

An evaluation of **economically valuable real-world tasks** across 44 occupations.
- 1,300+ tasks derived from real professional deliverables
- Evaluated by domain experts and automated graders
- Frontier models show improvement but **far from saturation**
- Highlights gaps between lab benchmarks and real work

### **EnigmaEval**
🔗 https://arxiv.org/html/2502.08859v1  

A benchmark of **long, unstructured, multimodal reasoning challenges** derived from puzzle hunts.
- 1,184 multimodal puzzles (text + images)
- Problems often require **hours or days for expert humans**
- Best frontier models achieve:
  - ~7% accuracy on standard puzzles
  - ~0% on hard subsets
- Designed to defeat shortcut reasoning and pattern matching

> Complements academic benchmarks by stressing **creative and lateral reasoning**.

### **Humanity’s Last Exam (HLE)**
🔗 https://github.com/centerforaisafety/hle  

A **frontier academic benchmark** designed to be the *final closed-ended exam* of its kind.
- 2,500 questions across mathematics, humanities, and natural sciences
- Multi-modal, expert-written, and globally curated
- Typical model accuracy: **~3%**
- Includes canary strings to prevent training contamination

## Contributing

Contributions are welcome. Please open an issue or PR with:
- Project / benchmark link
- Evidence of difficulty (e.g. reported success rates)
- What capability it stresses (reasoning, planning, execution, multimodality, etc.)

