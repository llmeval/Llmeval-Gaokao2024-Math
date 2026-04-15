<p align="center">
  <img src="llmeval-logo.png" width="200">
</p>

<h2 align="center">LLMEval-Gaokao2024-Math: 中文大语言模型评测 2024 高考数学专题</h2>

<p align="center">
  <a href="https://github.com/llmeval"><img src="https://img.shields.io/badge/组织-LLMEval-green.svg?style=for-the-badge" alt="LLMEval"></a>
</p>

> **注意：** 英文版 README 请参阅 [README.md](README.md)。

## 🔔 最新消息

- 📊 **[2024-06]** 2024 高考数学评测结果发布。

## 📚 评测介绍

全新出炉的高考试题具备高度的**独创性**和**保密性**，是用来评测大模型的**绝好评测集合**。复旦大学 NLP 实验室 LLMEval 团队将持续推出对 2024 高考数学真题的**系列评测**。

榜单持续更新，结果仅供参考。

### 核心特点

- **零污染风险** — 全新考试题目，模型在预训练阶段不可能接触
- **双格式 Prompt** — LaTeX 格式和转义符格式，测试模型对输入格式的敏感度
- **两套试卷** — 新 I 卷和新 II 卷
- **标准化评分** — 采用高考官方评分标准

## 📋 评测设计

每个模型在两套试卷上使用两种不同的 Prompt 格式进行评测：

| 试卷 | 格式 | 说明 |
|:-----|:-----|:-----|
| 新 I 卷 | LaTeX | 数学表达式使用标准 LaTeX 格式 |
| 新 I 卷 | 转义符 | 数学表达式使用文本转义符格式 |
| 新 II 卷 | LaTeX | 数学表达式使用标准 LaTeX 格式 |
| 新 II 卷 | 转义符 | 数学表达式使用文本转义符格式 |

双格式设计旨在揭示模型在数学场景下对 Prompt 格式的敏感程度。

## 🏆 评测结果

### 新 I 卷

- LaTeX 版 Prompt 测试结果：`新I卷/latex测试/`
- 转义符版 Prompt 测试结果：`新I卷/转义符测试/`

### 新 II 卷

- LaTeX 版 Prompt 测试结果：`新II卷/latex测试/`
- 转义符版 Prompt 测试结果：`新II卷/转义符测试/`

## 🔗 相关项目

| 项目 | 说明 | 链接 |
|------|------|------|
| **LLMEval**（AAAI 2024） | 评测方法论研究 | [arXiv](https://arxiv.org/abs/2312.07398) |
| **LLMEval-Fair**（ACL 2026） | 鲁棒公平评测，20 万+题 | [GitHub](https://github.com/llmeval/LLMEval-Fair) |
| **LLMEval-Med**（EMNLP 2025） | 医学大模型基准 | [GitHub](https://github.com/llmeval/LLMEval-Med) |
| **LLMEval-1** | 第一期通用能力评测 | [GitHub](https://github.com/llmeval/LLMEval-1) |
| **LLMEval-2** | 第二期专业领域评测 | [GitHub](https://github.com/llmeval/LLMEval-2) |
| **官方网站** | 全部项目与排行榜 | [llmeval.com](http://llmeval.com/) |

## 📝 引用

```bibtex
@misc{llmeval-gaokao2024-math,
  author = {LLMEval Team},
  title  = {LLMEval-Gaokao2024-Math},
  year   = {2024},
  url    = {https://github.com/llmeval/Llmeval-Gaokao2024-Math}
}
```

## 📞 联系我们

- **网站**：[http://llmeval.com/](http://llmeval.com/)
- **邮箱**：mingzhang23@m.fudan.edu.cn
- **微信**：zanyingluan

---

<p align="center">
  <b>LLMEval</b> | 复旦大学 NLP 实验室
</p>
