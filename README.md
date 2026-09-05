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

## 2026-09-06

## Diffusion Models

| 标题 | 评分 | Gemini 摘要 | 评分理由 | 原始摘要 |
|------|------|-------------|----------|----------|
| **[Conditioning Degenerate Diffusion Models](https://arxiv.org/abs/2609.04090v1)** | ⭐ 78/100 | 利用因果最优传输解决退化扩散模型引导问题 | 理论严谨且具有创新性，但应用场景相对垂直。 | <details><summary>展开</summary>Current conditioned generative models heavily rely on score functions for guidance during training. When the generative model is a diffusion process with a singular diffusion coefficient and the underlying (conditional) densities either do not exist or are not smooth, we use causal optimal transport to define \emph{approximate} loss functions that identify a minimum-entropy control for guidance under minimal assumptions. Our approach relies on causal optimal transport and its characterization through the predictable representation property of (conditioned) diffusion processes whose associated martingale problem is well posed, à la Üstünel.</details> |

