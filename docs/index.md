---
layout: default
title: "HF Hot"
---

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

## Updated on 2026.09.18
> Usage instructions: [here]({{ site.baseurl }}/README.html#usage)

<style>.paper-nav{display:flex;flex-wrap:wrap;gap:.45rem;margin:1rem 0 1.25rem 0}.paper-nav a{border:1px solid #d0d7de;border-radius:999px;padding:.32rem .7rem;text-decoration:none;color:#24292f;background:#fff;font-size:.92rem}.paper-nav a.active{background:#0969da;color:#fff;border-color:#0969da}</style>

<nav class="paper-nav"><a href="{{ site.baseurl }}/" class="active">HF Hot</a>
<a href="{{ site.baseurl }}/vla.html">VLA</a>
<a href="{{ site.baseurl }}/world-model.html">World Model</a>
<a href="{{ site.baseurl }}/rl.html">RL</a>
<a href="{{ site.baseurl }}/ego-policy.html">EGO Policy</a>
<a href="{{ site.baseurl }}/dexterous.html">Dexterous</a>
<a href="{{ site.baseurl }}/manipulation.html">Manipulation</a></nav>

## 🔥 HuggingFace Hot Papers

| Publish Date | Title & Abstract | Authors | Links |
|:---------|:-----------------------|:---------|:------|
| **2026-09-15** | **Fingers as Legs: Learning Self-Supported Locomotion and Manipulation with an Anthropomorphic Hand** `Dexterous` 🔥 HF#15<br>A walking robotic hand must use the same fingers to move its body, support its weight, and interact with the environment. We show how an anthropomorphic hand can learn these skills while retaining its finger design and position controller. Onboard power and computation make the platform self-contained. Our reinforcement learning approach accounts for the hand's unequal fingers, with training in a... | Robert Katzschmann Team | [ArXiv](http://arxiv.org/abs/2609.17172) |
| **2026-09-16** | **In-Context Robot Learning with VLM Agents** `VLA` `Manipulation` 🔥 HF#18<br>Enabling robots to adapt to unfamiliar environments as readily as humans remains a moonshot goal of embodied AI. No finite collection of demonstrations can cover every task and situation a robot will encounter, making the ability to learn from context at deployment essential for generalization. Such in-context learning (ICL), however, remains largely beyond the reach of existing robotic policies.... | Tong Wu Team | [ArXiv](http://arxiv.org/abs/2609.19138) / [Web](https://github.com/cheng-haha/GPT-Policy) |
| **2026-09-16** | **ActionPiece: Rethinking Action Tokenization for Autoregressive Vision-Language-Action Models** `VLA` 🔥 HF#27<br>Action tokenizers play a central role in autoregressive vision-language-action (VLA) models, determining both the targets for policy training and the executable commands recovered from predicted tokens. Their fidelity is commonly evaluated using pointwise reconstruction metrics such as mean squared error (MSE), yet small individual errors do not fully characterize how faithfully action... | Kai Chen Team | [ArXiv](http://arxiv.org/abs/2609.18487) / [Web](https://deepcybo-physai.github.io/ActionPiece/) |
| **2026-09-13** | **OmniHarness: Harnessing Generalizable Visual Generation via Symbolic Policy Learning** `HF-Hot` 🔥 HF#42<br>Unified multimodal large language models (MLLMs) and multi-agent systems have advanced visual generation. However, three limitations remain. (1) Existing methods often distill task-specific experience with limited generalizability. (2) Reflection is often deferred until task completion. (3) Knowledge is often acquired only in response to downstream task demands. To address these limitations, we... | Yan Shi Team | [ArXiv](http://arxiv.org/abs/2609.16057) |
| **2026-09-15** | **ImpossibleRubrics: Stress-Testing Generated Rubrics as Reward Signals** `HF-Hot` 🔥 HF#43<br>Language model-generated rubrics are increasingly used as reward signals for rubric-based reinforcement learning, LLM-as-a-judge evaluation, and automated grading. Such rubrics are reliable only if they reward honest answers over adversarial answers optimized to exploit them. Yet their robustness to such optimization remains poorly understood. We isolate the hardest regime: impossible tasks,... | Xi Yang Team | [ArXiv](http://arxiv.org/abs/2609.16816) |
| **2026-09-12** | **Convergent Emergence of In-Context Learning Across Modalities** `HF-Hot` 🔥 HF#44<br>Few-shot in-context learning (ICL), the capacity of a model to infer abstract patterns from input-output examples provided in its prompt and apply them to new inputs, has been extensively studied in large language models trained for next-token prediction on human text. Recently, few-shot ICL has been demonstrated in autoregressive genomic models as well. This raises a question: does ICL emerge... | Daniel Khashabi Team | [ArXiv](http://arxiv.org/abs/2609.14011) |
| **2026-09-13** | **Another Blueprint In The Wall: How to Ask Frontier AI Like a Kid?** `HF-Hot` 🔥 HF#45<br>This paper reports experiments across six frontier model types from OpenAI, Anthropic, xAI, and Google DeepMind. Ten independent sessions per model type used the same three stage prompt sequence, progressing from architectural preference to a full ASCII backbone. Under the school audience framing, responses repeatedly converged on a shared architectural pattern built around persistent latent... | Afshin Khadangi | [ArXiv](http://arxiv.org/abs/2609.14803) |
| **2026-09-14** | **ModularRSI: Modular and Generalizable Recursive Harness Self-Improvement** `HF-Hot` 🔥 HF#46<br>Recent work extends recursive self-improvement (RSI) to agent harnesses for long-horizon coding and terminal tasks, enabling agents to improve execution mechanisms from experience. However, generalizable harness RSI remains challenging. First, evolving harnesses on evaluation benchmarks or their subsets makes it difficult to distinguish reusable improvements from benchmark-specific adaptation.... | Chenghua Lin Team | [ArXiv](http://arxiv.org/abs/2609.14857) |
| **2026-09-14** | **HarnessVLN: Unifying Training-Free Embodied Navigation through an Agent Harness** `HF-Hot` 🔥 HF#47<br>Embodied navigation requires agents to interpret visual observations, accumulate spatial knowledge, and execute actions to follow instructions or locate objects. Training-based methods face generalization challenges, while training-free methods exploit multimodal large language models (MLLMs) but often lack mechanisms to reconcile proposed actions with spatial evidence, task progress, and... | Lan-Zhe Guo Team | [ArXiv](http://arxiv.org/abs/2609.15195) |
| **2026-09-12** | **StepAudio 3 Realtime Technical Report** `HF-Hot` 🔥 HF#48<br>Realtime spoken interaction demands deep reasoning, prompt responses, and fluid turn-taking. We present StepAudio 3 Realtime, an audio-language foundation model organized around a continuous listen-converse-think-act loop. Deep Perception captures rich acoustic cues to interpret user intent, while Seamless Duplex models synchronized audio streams to handle pauses, backchannels, and interruptions... | Zixuan Wang Team | [ArXiv](http://arxiv.org/abs/2609.14005) |
| **2026-09-11** | **StepAudio 3 Music Technical Report** `HF-Hot` 🔥 HF#49<br>We introduce StepAudio 3 Music, a large-scale, long-form music generation model that supports explicit musical planning and open-domain text-controlled generation. The StepAudio Music Tokenizer represents audio as a 50-Hz stream from a 65536-entry single codebook, using semantically informed self-supervised and multi-task training to preserve musical structure and reconstruction-relevant... | Chao Yan Team | [ArXiv](http://arxiv.org/abs/2609.16034) |
| **2026-09-14** | **Decoy Direction Optimization: A Post-Hoc Defense Against LLM Abliteration** `HF-Hot` 🔥 HF#50<br>Safety guardrails in open-weight language models can be readily bypassed using Refusal Feature Ablation (RFA), a technique that identifies and projects out a linear refusal direction from the residual stream, often achieving a high attack success rate (ASR) while preserving model capability. Defending against these attacks typically requires computationally expensive safety finetuning for every... | Virginia Smith Team | [ArXiv](http://arxiv.org/abs/2609.16204) |

[contributors-shield]: https://img.shields.io/github/contributors/ttylerzh/robotics_paper_daily.svg?style=for-the-badge
[contributors-url]: https://github.com/ttylerzh/robotics_paper_daily/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/ttylerzh/robotics_paper_daily.svg?style=for-the-badge
[forks-url]: https://github.com/ttylerzh/robotics_paper_daily/network/members
[stars-shield]: https://img.shields.io/github/stars/ttylerzh/robotics_paper_daily.svg?style=for-the-badge
[stars-url]: https://github.com/ttylerzh/robotics_paper_daily/stargazers
[issues-shield]: https://img.shields.io/github/issues/ttylerzh/robotics_paper_daily.svg?style=for-the-badge
[issues-url]: https://github.com/ttylerzh/robotics_paper_daily/issues