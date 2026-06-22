<div align="center">

# TencentQQ Multimodal Research

Open-source projects from the TencentQQ multimodal technology team for multimodal models, retrieval, evaluation, and efficient training systems.

[![GitHub organization](https://img.shields.io/badge/GitHub-Tencent--QQMM-181717?logo=github)](https://github.com/Tencent-QQMM)
[![Projects](https://img.shields.io/badge/projects-multimodal%20AI-blue)](https://github.com/Tencent-QQMM?tab=repositories)

</div>

## ✨ Latest Updates

- 🚀 **Jun 2026**: [Online Dynamic Batching](https://github.com/online-dynamic-batching/online-dynamic-batching) is now available as a dedicated training-system project, with the arXiv paper [Online Dynamic Batching with Formal Guarantees for LLM Training](https://arxiv.org/abs/2606.19989).
- 🧠 **Jun 2026**: [skill-evolver](https://github.com/Tencent-QQMM/skill-evolver) is released as an evidence-scored, safety-gated skill evolution framework for AI agents.
- 📚 **May 2026**: [LiveK12Bench](https://github.com/Tencent-QQMM/LiveK12Bench) is released for evaluating large multimodal models on high-school-level examinations, with the arXiv paper [LiveK12Bench](https://arxiv.org/abs/2605.26781).

## Focus Areas

| Area | Projects | What to find |
| --- | --- | --- |
| Multimodal models | [Video-CCAM](https://github.com/Tencent-QQMM/Video-CCAM), [PureMM](https://github.com/Tencent-QQMM/PureMM) | Video and multimodal model research, lightweight architectures, and training resources. |
| Embedding and retrieval | [QQMM-embed](https://github.com/Tencent-QQMM/QQMM-embed) | Multimodal representation learning and retrieval-oriented model resources. |
| Evaluation and reasoning | [LiveK12Bench](https://github.com/Tencent-QQMM/LiveK12Bench), [Fact-R1](https://github.com/Tencent-QQMM/Fact-R1), [ChipTuning](https://github.com/Tencent-QQMM/ChipTuning) | Benchmarks, reasoning studies, and analysis tools for multimodal systems. |
| Training systems | [Online Dynamic Batching](https://github.com/online-dynamic-batching/online-dynamic-batching) | Faster LLM and VLM fine-tuning with online post-preprocessing length observation. |
| Agent tools | [skill-evolver](https://github.com/Tencent-QQMM/skill-evolver) | Evidence-scored skill evolution workflows for AI agents. |

## Online Dynamic Batching

[Online Dynamic Batching](https://github.com/online-dynamic-batching/online-dynamic-batching) is maintained as a dedicated project under the [online-dynamic-batching](https://github.com/online-dynamic-batching) organization. It provides a DataLoader-side acceleration layer for variable-length LLM and multimodal fine-tuning without model, optimizer, attention-kernel, or dataset-format changes.

- Paper: [Online Dynamic Batching with Formal Guarantees for LLM Training](https://arxiv.org/abs/2606.19989)
- Package: [`online-dynamic-batching`](https://github.com/online-dynamic-batching/online-dynamic-batching)
- Integrations: Hugging Face Trainer, LLaMA-Factory, Accelerate, and Lightning adapters

## Start Here

- Browse all public repositories in [Tencent-QQMM](https://github.com/Tencent-QQMM?tab=repositories).
- Open each repository for installation, model, dataset, and benchmark-specific instructions.
- Use repository issues for project-specific questions and collaboration.

## About

TencentQQ Multimodal Research builds open-source model, evaluation, and training-system components for practical multimodal AI. This organization collects public projects from the team and links to closely related infrastructure projects maintained in dedicated organizations when a project grows into its own ecosystem.

<sub>Maintained by [Dian Li](https://github.com/lidian007).</sub>
