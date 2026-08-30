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

## 2026-08-31

## Machine Learning

| 标题 | 评分 | Gemini 摘要 | 评分理由 | 原始摘要 |
|------|------|-------------|----------|----------|
| **[TRACE-CRC: Trajectory-Adaptive Conformal Risk Control for Multi-Step Channel State Information Prediction](https://arxiv.org/abs/2608.27124v1)** | ⭐ 82/100 | 提出TRACE-CRC实现多步CSI预测的轨迹级不确定性量化 | 方法创新且严谨，有效解决了多步预测中的覆盖率与精度平衡问题。 | <details><summary>展开</summary>Reliable prediction of time-varying channel state information (CSI) is essential for efficient wireless communication. Each CSI frame is a matrix-valued representation of the wireless channel response, and a sequence of CSI frames forms a temporal channel trajectory. Modern deep learning-based CSI predictors, however, often provide only point predictions and lack calibrated uncertainty estimates. This limitation is particularly problematic in multi-step CSI prediction, where the target is a sequence of future CSI matrices, and downstream decisions such as beamforming or scheduling may fail if any part of the predicted trajectory is unreliable. We propose trajectory-adaptive calibration and error profiling with conformal risk control (TRACE-CRC), a method for trajectory-aware uncertainty quantification in multi-step CSI prediction. TRACE-CRC constructs Frobenius-norm uncertainty balls around predicted CSI matrices and controls the risk that at least one future frame is uncovered. Instead of calibrating each future step independently, TRACE-CRC combines future-step-dependent error profiling, trajectory difficulty stratification, and learn-then-test (LTT) risk control. Empirically, TRACE-CRC achieves reliable trajectory-level coverage with substantially smaller uncertainty balls than conservative multi-step corrections, while avoiding the trajectory undercoverage of compact stepwise and adaptive conformal baselines.</details> |
| **[Virtual iEEG from Scalp EEG: Charting the Landscape of Source Imaging, Intracranial Inference and Reconstruction](https://arxiv.org/abs/2608.26998v1)** | ⭐ 75/100 | 综述了从头皮EEG推断颅内EEG的方法与挑战 | 系统梳理虚拟iEEG框架，评估充分且具有实用价值 | <details><summary>展开</summary>Intracranial electroencephalography (iEEG) provides temporally precise and spatially specific access to neural activity from focal and deep brain regions, but its invasiveness and restricted anatomical coverage limit routine use. These constraints have motivated scalp-to-intracranial inference, termed virtual iEEG when model outputs carry iEEG-defined event, feature, representation, or contact-level waveform semantics. This review presents a target-centred framework distinguishing event inference, feature translation, and waveform reconstruction, while separating predictability from observability, identifiability, fidelity, and utility. Evidence is evaluated according to cohort independence, anatomical and spectral coverage, train--test separation, and target-patient adaptation. Current studies support inference of selected intracranial events, low-frequency components, and task-related representations, but not unique recovery of arbitrary contact-level activity. Stronger validation requires appropriate controls, source-imaging baselines, uncertainty assessment, and incremental-utility testing. Future progress depends on independent paired datasets and prospective evidence that virtual iEEG adds value beyond scalp EEG and EEG source imaging.</details> |

