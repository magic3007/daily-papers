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

## 2026-11-19

## Computer Vision

| 标题 | 评分 | Gemini 摘要 | 评分理由 | 原始摘要 |
|------|------|-------------|----------|----------|
| **[Beyond the Camera: A Tri-Modal Driving World Model for Future RGB, Thermal, and LiDAR Forecasting in Adverse Weather](https://arxiv.org/abs/2611.22669v1)** | ⭐ 78/100 | 提出首个RGB、热成像与激光雷达三模态驾驶世界模型 | 多传感器联合预测在恶劣天气下表现优异，方法严谨。 | <details><summary>展开</summary>Driving world models forecast what a vehicle's sensors will record next. Most forecast camera video and some add LiDAR, but thermal cameras, which still see in darkness and some adverse weather, are rarely a forecast target, and to our knowledge no world model forecasts all three sensors. We study joint forecasting of RGB, thermal, and LiDAR on real adverse-weather sequences of the DSERT-RoLL dataset. We post-train a pretrained video world model for each sensor and represent LiDAR as a depth video aligned with the RGB camera, with densification and encoding chosen by what the model's video tokenizer can reconstruct. A tri-sensor model sees all three sensors as one video. We score LiDAR in meters against measured returns and compare against persistence baselines passed through the same tokenizer as the model. With this matching, an apparent loss of the thermal model to persistence in fog disappears. On all 58 validation sequences in six weather conditions, post-trained RGB and thermal forecasts beat compression-matched persistence. Joint training lowers the LiDAR error at 2s by 2.1m at a small cost in camera fidelity, and only the tri-sensor model's LiDAR forecasts beat persistence in mean error. Blanking one sensor degrades the forecasts of the others more in snow than in fog.</details> |

