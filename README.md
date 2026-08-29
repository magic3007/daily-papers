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

## 2026-08-29

## Large Language Models

| 标题 | 评分 | Gemini 摘要 | 评分理由 | 原始摘要 |
|------|------|-------------|----------|----------|
| **[LAAF: A Layered Accountability Architecture Framework for LLM Applications](https://arxiv.org/abs/2608.27102v1)** | ⭐ 78/100 | 提出LLM问责框架LAAF | 研究方法严谨，框架具有创新性和实用性，但仍有待实证验证。 | <details><summary>展开</summary>Large Language Models (LLMs) operate in hospitals, courtrooms, banks, and public service desks, where fluent, confident outputs are treated as authoritative even when ungrounded or incorrect. When such an output contributes to harm, who is answerable, and through what mechanisms can responsibility be traced, explained, and acted upon? Following PRISMA guidance, five databases were searched from January 2022 to March 2026 against four review questions; of 4,512 records identified, 122 primary studies were included, together with 12 regulatory and standards documents analysed as primary sources. The review consolidates a sociotechnical account of accountability as an actor-forum relation resolved into five dimensions, and synthesises mechanisms across four families: technical controls, human oversight, organisational governance, and documentation and traceability, each with a maturity assessment. The corpus is read through a four-layer classification device spanning provenance, application logic, human oversight, and governance and redress, cross-cut by traceability, role clarity, and continuous monitoring. Both are mapped onto the EU AI Act, whose high-risk obligations have applied since 2 August 2026, the NIST AI RMF with its Generative AI Profile, ISO/IEC 42001, and sectoral guidance in healthcare, consumer finance, education, and the public sector. Four persistent gaps emerge: under-specification of human oversight, absence of shared accountability metrics, disciplinary disconnection, and limited empirical evaluation, alongside five structural tensions that no surveyed instrument resolves. The review closes by consolidating the classification device into an integrated accountability architecture, LAAF, with cybersecurity aligned to the OWASP LLM Top 10 (2025); it is a synthesis of the surveyed evidence rather than a validated artefact.</details> |

## Machine Learning

| 标题 | 评分 | Gemini 摘要 | 评分理由 | 原始摘要 |
|------|------|-------------|----------|----------|
| **[Linear Independence of Polynomial Compositions and Identifiability of Deep Neural Networks](https://arxiv.org/abs/2608.27113v1)** | ⭐ 75/100 | 证明多项式复合线性无关性并刻画深度网络可辨识性 | 理论贡献显著，数学推导严谨，对深度学习基础理论有价值 | <details><summary>展开</summary>Motivated by theoretical problems in deep learning, we conjecture that post-composing a fixed number of pairwise distinct nonconstant polynomials with a generic polynomial of sufficiently large degree yields linearly independent polynomials. This generalizes Newman--Slater's theorem on powers of polynomials. We establish several cases of this conjecture and its origin-passing variant: We prove the result for two polynomials, and for an arbitrary number of polynomials when their degrees are bounded. Furthermore, we show how the conjecture implies a complete understanding of the identifiability (i.e., parameter symmetries) of deep fully connected neural network architectures with generic polynomial activation functions. In particular, for network architectures with layer-specific activations of increasing degree, our established versions of the conjecture fully characterize the set of parameters yielding the same end-to-end network function. As a special case, we fully resolve the identifiability of shallow polynomial networks.</details> |

