---
layout: default
title: "HF Hot"
---

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

## Updated on 2026.09.26
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
| **2026-09-23** | **DeltaWAM: Delta World Action Models for Bimanual Manipulation** `World Model` 🔥 HF#8<br>World-action models (WAMs) transfer visual and motion priors from pretrained video generators to robot control by jointly modeling visual dynamics and actions. Existing WAMs, however, predict dense future frames during training, repeatedly modeling largely unchanged content and coupling action-conditioned dynamics to nuisance appearance variations. At inference, processing each complete... | Hao Tang Team | [ArXiv](http://arxiv.org/abs/2609.28811) |
| **2026-09-24** | **World Action Agent: Harnessing VLMs for Robot Manipulation via World Action Rehearsal** `VLA` `Dexterous` `Manipulation` 🔥 HF#16<br>General-purpose vision-language models (VLMs) bring broad knowledge and spatial reasoning to robot manipulation, yet existing systems either use them indirectly, to predict constraints or write programs, or give them a view of the scene rather than a world in which to act. We present World Action Agent (WAA), a multi-agent harness through which VLMs pilot robots with basic tools, making every... | Zexi Li Team | [ArXiv](http://arxiv.org/abs/2609.29964) |
| **2026-09-21** | **X-Planner: Event-Structured Task Planning for Embodied Intelligence** `VLA` `EGO Policy` 🔥 HF#27<br>Task planning bridges high-level instructions and executable behavior in long-horizon manipulation, yet modern Vision-Language-Action (VLA) systems often leave this intermediate structure implicit. Existing chain-of-thought (CoT) planners also tend to rely on coarse task-level annotations or serialize long reasoning traces token by token. We present X-Planner, a planning front-end that addresses... | Qian Wang Team | [ArXiv](http://arxiv.org/abs/2609.25187) / [Web](https://github.com/X-Square-Robot/Xplanner) |
| **2026-09-23** | **EmbodiedSWE: Coding Agents for Long Horizon Dexterous Robotics** `VLA` 🔥 HF#40<br>We study coding agents for long-horizon, dexterous robotics and ask whether their solutions can provide scalable supervision for learning general robot policies. To test this, we develop EMBODIEDSWE-BENCH, a simulation benchmark for coding agents spanning contact-rich manipulation, deformable objects, and long-horizon tasks requiring up to half an hour of continuous interaction. We find that... | Canwen Xu Team | [ArXiv](http://arxiv.org/abs/2609.27308) |
| **2026-09-23** | **MemBodied: Recurrent Associative Memory for Vision-Language-Action Models** `VLA` `Dexterous` 🔥 HF#42<br>Vision-Language-Action models provide a strong foundation for general-purpose robot control, yet a vast majority of policies do not preserve and leverage episode-level information beyond the current observation. This limitation is consequential in history-dependent manipulation tasks that depend on information available only in past observations. Retaining past observations in context can aid in... | Soujanya Poria Team | [ArXiv](http://arxiv.org/abs/2609.28256) |
| **2026-09-23** | **InternW0: A Foundational Physical World Model for Efficient Real-World Interactions** `Manipulation` `Dexterous` 🔥 HF#49<br>Physical intelligence requires more than predicting how the world may evolve: predictions must remain actionable as the world continues to change. We introduce InternW0, the first instantiation of the InternW physical world model series from Shanghai AI Laboratory, built around omnimodal interfaces, asynchronous multi-frequency processing, and local physical modeling under partial observations... | Weinan Zhang Team | [ArXiv](http://arxiv.org/abs/2609.27656) |

[contributors-shield]: https://img.shields.io/github/contributors/ttylerzh/robotics_paper_daily.svg?style=for-the-badge
[contributors-url]: https://github.com/ttylerzh/robotics_paper_daily/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/ttylerzh/robotics_paper_daily.svg?style=for-the-badge
[forks-url]: https://github.com/ttylerzh/robotics_paper_daily/network/members
[stars-shield]: https://img.shields.io/github/stars/ttylerzh/robotics_paper_daily.svg?style=for-the-badge
[stars-url]: https://github.com/ttylerzh/robotics_paper_daily/stargazers
[issues-shield]: https://img.shields.io/github/issues/ttylerzh/robotics_paper_daily.svg?style=for-the-badge
[issues-url]: https://github.com/ttylerzh/robotics_paper_daily/issues