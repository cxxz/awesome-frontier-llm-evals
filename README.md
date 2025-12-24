## Frontier LLM Evaluations

This repository tracks emerging, challenging and frontier evaluation tasks for foundation models including LLMs and VLMs. Many existing benchmarks are saturating as model capabilities improve; our focus is on scenarios where top‑tier models still struggle, typically achieving less than 60% success. We include open‑source benchmarks, research platforms, and challenging datasets that probe reasoning, planning and real‑world task execution. Obsolete projects and saturated benchmarks are periodically pruned so that this list stays aligned with the frontier.

## Principles

* **Frontier difficulty**: we highlight tasks where leading models consistently score well below 60% accuracy or success, exposing current limitations.
* **Realism and diversity**: the benchmarks encompass long‑context reasoning, multimodal puzzles, remote work projects, systems research tasks and economically valuable occupations.
* **Open evaluation**: each resource provides transparent evaluation protocols, verifiable solutions or human‑graded scoring, enabling reproducibility and fair comparison.

## Frontier Benchmarks & Platforms

### **Frontier-CS**
🔗 https://github.com/FrontierCS/Frontier-CS  

An unsolved, open-ended, verifiable and diverse benchmark for AI on challenging computer science problems. It offers algorithmic and research tasks with continuous scoring rather than binary pass-fail, encouraging iterative improvement. Frontier-CS probes problems with no known optimal solutions, pushing models beyond saturated coding contests.

### **ADRS – AI-Driven Research for Systems**
🔗 https://github.com/UCB-ADRS/ADRS  

ADRS uses AI to generate, evaluate and refine algorithms for performance-oriented systems tasks, such as mixture-of-experts placement, multi-region cloud scheduling, LLM-SQL optimization and transaction scheduling. The framework emphasizes reliable verifiers so AI-generated solutions can be automatically validated against predefined workloads.

### **Remote Labor Index (RLI)**
🔗 https://www.remotelabor.ai  

A multi-sector benchmark of real remote work projects that measures AI automation in practical settings. RLI contains projects spanning game development, product design, architecture, data analysis and video animation. It represents more than 6,000 hours of human labor valued at over $140,000.

### **GDPval (OpenAI)**
🔗 https://openai.com/index/gdpval/  

An economically oriented evaluation introduced by OpenAI that measures model performance on real-world tasks across 44 occupations. The dataset includes 1,320 specialized tasks (220 in the public gold set) derived from deliverables such as legal briefs, engineering blueprints and nursing care plans. Expert graders compare AI-generated outputs to human work using detailed scoring rubrics. GDPval provides a transparent basis for tracking improvements in economically valuable capabilities.

### **EnigmaEval**
🔗 https://arxiv.org/html/2502.08859v1  

A benchmark of 1,184 long multimodal puzzles drawn from puzzle hunts that test implicit knowledge synthesis and multi-step deductive reasoning. Each puzzle combines text and images and may take human teams hours or days to solve. EnigmaEval includes both the original multimodal problems and human-transcribed versions to separate reasoning from preprocessing limitations.

### **Humanity's Last Exam (HLE)**
🔗 https://github.com/centerforaisafety/hle  

A multimodal academic benchmark comprising 2,500 closed-ended questions across dozens of subjects including mathematics, humanities and natural sciences. Designed to be the final closed-ended exam of its kind, HLE provides multiple-choice and short-answer questions suitable for automated grading.

## Contributing

Contributions are welcome. Please open an issue or PR with:
- Project / benchmark link
- Evidence of difficulty (e.g. reported success rates)
- What capability it stresses (reasoning, planning, execution, multimodality, etc.)

