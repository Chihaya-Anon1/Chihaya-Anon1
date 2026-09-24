# Chihaya

`Python` `Java` `RAG / LLM 应用` — 关注能真正落地的 AI 工程，习惯用数据验证结论。

---

### 我在做的事

**🔍 企业知识库 RAG 问答系统** · [ai-demo](https://github.com/Chihaya-Anon1/ai-demo)

FastAPI + LangChain + ChromaDB + DeepSeek，从 PDF 解析、切分、向量化、检索到生成全链路自己实现。

- 语料：34 份公开技术论文，**949 页 / 322.7 万字 → 10,643 个文本块**
- 检索：Top-3 **文档级命中率 97.1%**（Top-1 94.1%），单次平均 **65ms**
- 端到端（检索 + 大模型生成）：平均 **0.97s**
- 工程排障：修复"每次查询全量拉取全库"的性能问题，**532ms → 90ms（5.9 倍）**且输出上下文逐字一致；修复大规模语料下 ChromaDB 分批写入超限

**🎓 本科毕业论文** · 基于知识蒸馏的轻量化卷积神经网络图像识别

以 ResNet-50 为教师、MobileNetV3-Small 为学生，引入坐标注意力并提出异构师生网络的"逻辑优先"非对称权重蒸馏策略，CIFAR-100 准确率 **48.11% → 56.14%**（+8.03 个百分点），并用 Grad-CAM 做可解释性验证。

---

### 技术栈

`Python` `FastAPI` `PyTorch` `LangChain` `ChromaDB` `RAG`
`Java` `SpringBoot` `JDBC` `MySQL` `Docker` `Linux` `Git`
`C` `ARM` `HarmonyOS / openHarmony`

---

### 正在寻找

AI 应用开发 / 大模型应用 / Python 后端 方向的机会。
