# Awesome-AI-Benchmarking
## Top AI Benchmarking Tools & Leaderboards Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on LLM Evaluation, Benchmarking & Leaderboards*  
**Last updated: March 2026**

This repository tracks notable **platforms** and **open-source projects** for **AI benchmarking and LLM evaluation**. These tools and leaderboards provide standardized, reproducible ways to measure model performance across reasoning, coding, knowledge, safety, instruction following, and real-world capabilities.

**Examples** include LMSYS Chatbot Arena, Artificial Analysis, Open LLM Leaderboard (Hugging Face), Vellum LLM Leaderboard, and LiveBench (the category leaders). Tools listed here emphasize **rigorous evaluation**, human voting, automated metrics, contamination-free testing, and multi-dimensional scoring.

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom benchmarking, local evaluation, and full transparency — ideal for researchers, companies, and developers who want reproducible and auditable results.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS / Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS / Hosted Platforms

### Core Benchmarking Platforms & Leaderboards

- **[LMSYS Chatbot Arena](https://lmarena.ai/)** (formerly Chatbot Arena)  
  The most popular human-voted blind arena for comparing LLMs through crowdsourced Elo ratings. Highly trusted for real-world conversational ability.

- **[Artificial Analysis](https://artificialanalysis.ai/)**  
  Independent, high-quality benchmarking platform with detailed metrics on quality, speed, price, latency, and context window.

- **[Open LLM Leaderboard (Hugging Face)](https://huggingface.co/spaces/open-llm-leaderboard/open_llm_leaderboard)**  
  The gold standard automated leaderboard for open models across multiple academic and reasoning benchmarks.

- **[LiveBench](https://livebench.ai/)**  
  Contamination-resistant benchmark with frequently updated questions to prevent data leakage.

- **[Vellum LLM Leaderboard](https://www.vellum.ai/llm-leaderboard)**  
  Enterprise-focused leaderboard with practical business use case evaluations.

### Advanced & Specialized Platforms

**Other notable mentions**: Arena (various forks), HELM, BigBench, and industry-specific benchmarks (e.g., Legal, Medical, Finance).

## Open-Source GitHub Projects

### Dedicated Benchmarking & Evaluation Frameworks

- **[lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness)**  
  The most widely used open-source framework for evaluating LLMs. Supports dozens of benchmarks with standardized, reproducible evaluation.

- **[Open LLM Leaderboard](https://github.com/huggingface/open-llm-leaderboard)**  
  Official open-source codebase behind Hugging Face’s popular leaderboard. Fully customizable for running your own evaluations.

- **[HELM (Holistic Evaluation of Language Models)](https://github.com/stanford-crfm/helm)**  
  Stanford’s comprehensive benchmarking suite covering accuracy, calibration, robustness, fairness, bias, and toxicity.

- **[LiveBench](https://github.com/livebench/livebench)**  
  Open-source contamination-free benchmark with regularly refreshed questions across multiple categories.

- **[EvalPlus](https://github.com/evalplus/evalplus)**  
  Rigorous evaluation framework focused on code generation with extended test cases (HumanEval+, MBPP+).

- **[DeepEval](https://github.com/confident-ai/deepeval)**  
  Popular open-source framework for LLM evaluation with RAGAs, G-Eval, and custom metrics.

- **[LangChain / LangSmith Evaluators](https://github.com/langchain-ai/langsmith-sdk)**  
  Production-grade evaluation tools with tracing and custom metric support.

- **[LightEval](https://github.com/huggingface/lighteval)**  
  Hugging Face’s lightweight and fast evaluation library optimized for large-scale benchmarking.

- **[Big-Bench](https://github.com/google/BIG-bench)**  
  Google’s massive collaborative benchmark with over 200+ diverse tasks.

### Additional Strong Open-Source Options

- **[LLM-KG-Bench](https://github.com/AKSW/LLM-KG-Bench)** — Knowledge graph and structured reasoning evaluation.
- **[RAGAS](https://github.com/explodinggradients/ragas)** — Specialized framework for evaluating Retrieval-Augmented Generation systems.
- **[PromptBench](https://github.com/microsoft/promptbench)** — Robustness and adversarial testing for prompts.
- **[SafetyBench](https://github.com/thu-coai/SafetyBench)** — Safety and alignment evaluation suites.
- **[MT-Bench](https://github.com/lm-sys/FastChat)** — Multi-turn conversation benchmarking (from LMSYS).
- **AgentBench** — For evaluating autonomous AI agents.
- **[ClawBench](https://github.com/reacher-z/ClawBench)** — Live-website browser-agent benchmark; 283 everyday tasks (V1 153 + V2 130) across 163 live platforms. Two-stage scoring: HTTP-request interception at per-task URL/method schema + LLM judge on intercepted payload. [Paper](https://arxiv.org/abs/2604.08523) · [Live leaderboard](https://claw-bench.com).
- Many community forks and extensions of `lm-evaluation-harness` for domain-specific benchmarks (finance, legal, medical, etc.).

**Frameworks for building custom benchmarks**: Use **lm-evaluation-harness** + **LightEval** + **DeepEval** combined with **LangGraph** for comprehensive, reproducible evaluation pipelines that can run locally or at scale.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Benchmark scores can be misleading without understanding the methodology, contamination risks, and specific use cases. Always interpret results in context.
- Different benchmarks favor different model strengths — no single leaderboard tells the full story.

---

**Made for AI researchers, LLM engineers, product teams, and open-source enthusiasts.**  
Let's make AI evaluation more transparent, rigorous, and reproducible.



## 📈 Star History

<div align="center">
  <a href="https://www.star-history.com/?repos=ishandutta2007%2FAwesome-AI-Benchmarking&type=date&legend=bottom-right">
   <picture>
     <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-AI-Benchmarking&type=date&theme=dark&legend=bottom-right" />
     <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-AI-Benchmarking&type=date&legend=bottom-right" />
     <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-AI-Benchmarking&type=date&legend=bottom-right" />
   </picture>
  </a>
</div>

