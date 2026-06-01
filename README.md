<p align="center">
  <a href="notebooks/phase1_intro/01_什么是量化金融.ipynb">
    <img src="notebooks/phase1_intro/yibo-quant.jpg" width="100%" alt="和Yibo零基础学习量化金融 · 从Python到AI量化交易实战" style="max-width: 920px; border-radius: 8px;"/>
  </a>
</p>

<p align="center">
  <strong>Quant-for-Beginners</strong> · 中文零基础量化金融 Notebook 路线 · Phase 1 已上线
</p>

<p align="center">
  <a href="requirements.txt"><img src="https://img.shields.io/badge/Python-3.10%2B-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/></a>
  <a href="notebooks/"><img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter"/></a>
  <a href="notebooks/phase1_intro/"><img src="https://img.shields.io/badge/Phase_1-4_chapters-2ea043?style=flat-square" alt="Phase 1"/></a>
</p>

<p align="center">
  <a href="#快速开始">快速开始</a> ·
  <a href="#课程目录">课程目录</a> ·
  <a href="#学习路线">学习路线</a> ·
  <a href="#路线图">后续规划</a>
</p>

---

## 简介

面向**零基础**读者的中文量化金融教程。每章可在约 30 分钟内跑通：**真实数据 → 收益率分析 → 双均线策略 → 回测评估**。

本仓库由 **Yibo** 整理维护：侧重可运行的 Notebook 与清晰图示，而非堆砌公式。内容持续更新，欢迎 Star 以便后续查阅。

| 项目 | 说明 |
|------|------|
| 形式 | Jupyter Notebook + 配套交互 HTML |
| 数据 | `yfinance` 免费日线行情 |
| 第一期 | 4 章（已全部上线） |
| 不适合 | 已具备完整回测框架、仅需高级因子参考的读者 |

---

## 快速开始

```bash
git clone https://github.com/yibohere/Quant-for-Beginners.git
cd Quant-for-Beginners
pip install -r requirements.txt
jupyter lab
```

---

## 课程目录
| 章 | 主题 | Notebook | 你将完成 |
|:--:|------|----------|----------|
| 01 | 什么是量化金融 | [打开](notebooks/phase1_intro/01_什么是量化金融.ipynb) | 建立量化直觉；下载真实 AAPL 行情 |
| 02 | 你的第一个量化实验 | [打开](notebooks/phase1_intro/02_你的第一个量化实验.ipynb) | OHLCV、收益率、波动对比 |
| 03 | 移动平均线策略 | [打开](notebooks/phase1_intro/03_移动平均线策略.ipynb) | MA5/MA20、金叉/死叉、首个交易规则 |
| 04 | 策略回测 | [打开](notebooks/phase1_intro/04_策略回测.ipynb) | 模拟交易、净值曲线、胜率与回撤 |

**配套演示**：[布朗运动与随机游走](assets/interactive/brownian-random-walk.html)（浏览器本地打开，对应第一章理论部分）

---

## 章节预览

<p align="center">
  <img src="assets/images/ch01_real_stock.png" width="48%" alt="第一章"/>
  <img src="assets/images/ch02_returns.png" width="48%" alt="第二章"/>
</p>
<p align="center">
  <img src="assets/images/ch03_ma_signals.png" width="48%" alt="第三章"/>
  <img src="assets/images/ch04_backtest.png" width="48%" alt="第四章"/>
</p>

<p align="center"><sub>章节示意图见 <code>assets/images/</code>；本地运行 Notebook 可得到交互式图表</sub></p>

---

## 学习路线

```
Phase 1（当前）
├── 01 量化认知与真实数据
├── 02 收益率与数据分析
├── 03 双均线策略
└── 04 策略回测

Phase 2（规划）  风险指标 · 波动率 · 多标的分析
Phase 3（规划）  因子 · 组合 · 夏普比率
Phase 4（规划）  机器学习与 AI 量化
```

| 章节 | 进度称号 |
|------|----------|
| 第 1 章 | Lv.1 量化探索者 |
| 第 2 章 | Lv.1 数据分析 |
| 第 3 章 | Lv.2 策略设计师 |
| 第 4 章 | Lv.3 回测分析师 |

---

## 仓库结构

```
Quant-for-Beginners/
├── notebooks/phase1_intro/   # 第一期课程
├── assets/
│   ├── images/               # README 与传播用配图
│   └── interactive/          # 独立 HTML 演示
├── scripts/                  # 配图生成、Notebook 维护脚本
├── docs/ROADMAP.md           # 详细路线图
├── src/                      # 可复用模块（建设中）
└── requirements.txt
```

---

## 后续规划

| 章节 | 主题 | 状态 |
|------|------|------|
| 05 | AI 预测涨跌（入门） | 规划中 |
| 06 | XGBoost 量化策略 | 规划中 |
| 07 | LSTM 时间序列 | 规划中 |
| 08 | Transformer 交易 | 规划中 |
| 09 | 多因子选股 | 规划中 |
| 10 | AI 量化系统搭建 | 规划中 |

完整说明见 [docs/ROADMAP.md](docs/ROADMAP.md)。

---

## Star 趋势

<p align="center">
  <img alt="GitHub stars" src="https://img.shields.io/github/stars/yibohere/Quant-for-Beginners?style=for-the-badge&logo=github&label=Stars&cacheSeconds=60" />
</p>

<p align="center">
  <a href="https://www.star-history.com/#yibohere/Quant-for-Beginners&Date">
    <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=yibohere/Quant-for-Beginners&type=date&legend=top-left" width="700" />
  </a>
</p>
---

## 贡献

欢迎提交 Issue / Pull Request：文案优化、图示改进、示策略例与勘误。

---

## 免责声明

本仓库仅供学习与研究，**不构成任何投资建议**。历史回测结果不代表未来表现，市场有风险。

---

<p align="center">
  <sub>如果这份路线对你有帮助，欢迎 Star</sub>
</p>
