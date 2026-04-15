## Hi there 👋, Alibaba-VELLDEPTH🌪️

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

## News

🎉 **Three papers have been accepted to ACL 2026 (Main Conference)!**

---

- **Seeing but Not Thinking: Routing Distraction in Multimodal Mixture-of-Experts**

  We identify a striking paradox in multimodal MoE models: they can accurately perceive visual content yet fail at subsequent reasoning — even when the same question is answered correctly in text-only settings. We term this the **Routing Distraction Hypothesis**: task-relevant domain experts are insufficiently activated when visual inputs are provided, despite the model possessing the required reasoning capability.

  Through cross-modal concept intervention experiments, expert activation analysis, and a lightweight **inference-time routing guidance strategy**, we demonstrate that softly boosting domain expert weights restores reasoning performance, achieving up to **+3.17% improvement** across six benchmarks and three multimodal MoE models of varying scales.

  *ArXiv and code coming soon.*

---

- **[Why Steering Works: Toward a Unified View of Language Model Parameter Dynamics](https://arxiv.org/pdf/2602.02343)**

  We propose a **unified mathematical framework** that reconciles three major controllable generation paradigms — local weight editing, LoRA, and steering vectors — as instances of the same dynamic weight update driven by an intervention intensity coefficient *m*.

  Under this lens, we introduce a **Preference–Utility analysis** that characterizes a consistent behavior curve across methods: preference odds increase linearly in a small-*m* regime, but utility collapses and preference saturates under over-intervention. We explain this via an **activation manifold** perspective and derive a joint optimization objective that extends the effective linear regime for more robust controllable generation.

---

- **[How Controllable Are Large Language Models? A Unified Evaluation across Behavioral Granularities](https://arxiv.org/pdf/2603.02578)**

  We introduce **SteerEval**, a domain-extensible benchmark for evaluating LLM controllability across behavioral granularities, grounded in Marr's three-level theory.

  SteerEval decomposes control targets into three levels — **L1 (Computational)**: *what* to express; **L2 (Algorithmic)**: *how* to express it; **L3 (Implementational)**: *how to instantiate it* with verifiable surface constraints — covering personality, emotion, and linguistic style domains. Evaluation of prompting-based and activation-intervention-based methods reveals a consistent finding: **control degrades significantly at finer granularities (especially L3)** for activation-based methods, while prompting-based approaches remain comparatively stable, pointing to a clear gap for future work in fine-grained behavioral compliance.

---


## News

🎉 **Three papers from the VELLDEPTH team have been accepted to CVPR 2026 (Main Conference)!**

- **SimplePoster**  
  A minimalist inpainting framework for poster generation that enables **faithful subject preservation** and **position-controllable text rendering** without extra control modules.  
  In Taobao product poster generation, SimplePoster introduces **spatial understanding into generative training** to address text learning difficulties, while removing redundant modular designs to improve controllability. It achieves **98.7% strict subject preservation**, outperforming SeedEdit3.0 (55.2%) and PosterMaker (85.3%).

  *ArXiv and code coming soon.*
  
- **[TC-Padé: Trajectory-Consistent Padé Approximation for Diffusion Acceleration](https://arxiv.org/pdf/2603.02943)**  
  A diffusion acceleration framework designed for practical **low-step sampling**.  
  TC-Padé uses **trajectory-consistent rational approximation** to model feature evolution more accurately than Taylor-based extrapolation, achieving strong speed-quality trade-offs across image and video generation models.  
  [[Code]](https://github.com/Alibaba-YuFeng/TC_Pade)

- **[Diffusion Probe: Generated Image Result Prediction Using CNN Probes](https://arxiv.org/abs/2602.23783)**  
  This work shows that **final generation quality can often be predicted at an early denoising stage** in diffusion models.  
  Through CNN probes, it provides a model-agnostic way to estimate image outcomes early, with applications in **prompt optimization**, **seed selection**, and **accelerated RL training**.  
  [[Code]](https://github.com/Alibaba-YuFeng/DiffusionProbe)

More updates and open-source projects from **VELLDEPTH** are coming soon.

