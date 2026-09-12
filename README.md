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

## 2026-09-13

## Computer Vision

| 标题 | 评分 | Gemini 摘要 | 评分理由 | 原始摘要 |
|------|------|-------------|----------|----------|
| **[A Two-Mirror Faceted Projection System for EUV Lithography](https://arxiv.org/abs/2609.11299v1)** | ⭐ 82/100 | 提出双镜面EUV光刻系统以提升光学效率 | 创新性光学架构设计，理论严谨且仿真结果优异 | <details><summary>展开</summary>We propose an all-reflective two-mirror projection system for extreme ultraviolet (EUV) lithography operating at exposure wavelengths of $13.5$~nm (Mo/Si) and $11.2$~nm (Ru/Be), delivering a fourfold ($4\times$) demagnification of the periodic mask pattern at a numerical aperture approaching unity ($\mathrm{NA}_{\max} \approx 0.993$). In contrast to conventional EUV projection objectives that incorporate 6--10 aspheric mirrors with an overall optical throughput of less than $15\%$, the proposed design redirects each accepted discrete spatial diffraction order scattered by the mask onto the wafer via a dedicated pair of planar mirror facets. The number of reflections is strictly fixed at two for all accepted orders, retaining $50$--$60\%$ of the power leaving the mask in each accepted order. We derive a spatial geometry providing rigorous optical path length equalization across all diffraction orders, thereby removing order-dependent propagation phase shifts. Individually optimized 30-bilayer Bragg multilayer coatings are designed for each facet using the transfer matrix method combined with global evolutionary optimization algorithms. The architecture is generalized to a three-dimensional vector formulation with a two-dimensionally periodic mask. Utilizing inverse lithography technology, Fourier parameterization, and a differentiable electromagnetic modal waveguide solver, we solve the synthesis problem for binary absorber masks (La absorber on a Ru/Be/Sr multilayer mirror). We demonstrate simulated aerial images of sub-10-nm features on the wafer (isolated peaks with a full width at half maximum (FWHM) of approximately $5.4$~nm and line pairs with a critical dimension of $6$~nm) and find that the two peaks remain resolved for the tested wafer defocus values from $0$ to $5$~nm along the $z$-axis.</details> |

