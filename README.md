# Daily Papers - 自动化每日精选 arxiv 论文

**自动抓取ArXiv论文，使用 Google Gemini 评分筛选高质量内容**

专为 **计算机科学学者/程序员** 设计

## ✨ 特性

- **🆓 完全免费** - 使用 Google AI Studio 免费 API
- **🤖 自动运行** - GitHub Actions 每天自动运行
- **🎯 智能评分** - 四维度评估（0-100分）
- **💡 AI摘要** - 自动生成论文核心贡献摘要

## 🚀 快速开始

1. **Fork 本仓库**
2. **配置 API Key** - 添加 `GOOGLE_AI_API_KEY` 到 GitHub Secrets（[获取地址](https://aistudio.google.com/apikey)）
3. **启用 Actions** - Actions → Daily Papers → Enable workflow
4. **订阅通知** - Watch → All Activity

完成！系统每天 UTC 17:00（北京时间 1:00）自动运行。

📖 **详细设置请查看 [SETUP.md](SETUP.md)**

## 📚 历史论文

查看所有历史精选论文：[papers](papers/)

---

<!-- PAPERS_START -->

## 2026-08-30

## Computer Vision

| 标题 | 评分 | Gemini 摘要 | 评分理由 | 原始摘要 |
|------|------|-------------|----------|----------|
| **[Differentiable Jitter Correction using Deep Learning-based Image Quality Metric for Phase-Contrast Micro-CT](https://arxiv.org/abs/2608.27034v1)** | ⭐ 72/100 | 基于深度学习的微CT抖动校正 | 创新性强，实用价值高，方法严谨，表述清晰。 | <details><summary>展开</summary>This paper proposes a fully differentiable jitter correction method for X-ray phase-contrast micro computed tomography using a deep learning-based image quality metric that estimates and compensates per-projection rigid jitter directly from the acquired projection data, without a pre-scan motion-free reference. The approach builds on a gradient-based auto-focus strategy adapted to parallel-beam geometry. A set of candidate objective functions is benchmarked in a controlled study, and the sensitivity of the visual information fidelity (VIF) metric to the jitter artifact is verified with the target phase-contrast data. To operate without a clean reference, a compact 3D convolutional neural network is trained to predict the VIF score from a single corrupted volume. A spatially selective total variation penalty applied exclusively to the image background is introduced to penalize spurious high-frequency structures that otherwise emerge during optimization. Experiments on biological specimens acquired at different synchrotron beamlines are conducted. Evaluation uses jitter motion applied to simulated and experimentally acquired projection data. The result confirms that the integrated pipeline reliably recovers fine structural detail lost due to jitter, with generalization demonstrated across morphologically distinct samples.</details> |

