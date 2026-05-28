# AI 学习计划

> 目标:从零基础到能独立做出 AI 应用 / 复现论文 / 微调模型
> 总周期:约 6 个月(每周 8–12 小时,可根据自身节奏调整)

---

## 阶段 0:数学与编程基础(2 周)

**目标**:补齐看懂模型公式、读懂代码所需的基本功。

- 数学
  - 线性代数:向量、矩阵运算、特征值、SVD
  - 概率统计:期望、方差、贝叶斯、常见分布
  - 微积分:偏导数、梯度、链式法则
  - 推荐资源:3Blue1Brown《线性代数的本质》《微积分的本质》
- Python
  - 语法、面向对象、装饰器、生成器
  - NumPy / Pandas / Matplotlib
- 工具链
  - Git / GitHub
  - VS Code 或 PyCharm
  - Conda / venv 虚拟环境

**产出**:用 NumPy 手写一个线性回归 + 梯度下降。

---

## 阶段 1:机器学习入门(3 周)

**目标**:理解经典 ML 算法的原理与适用场景。

- 监督学习:线性回归、逻辑回归、决策树、随机森林、SVM、KNN
- 无监督学习:K-Means、PCA、层次聚类
- 模型评估:训练/验证/测试集、交叉验证、过拟合、正则化
- 评价指标:Accuracy / Precision / Recall / F1 / AUC / RMSE
- 推荐资源
  - 吴恩达《Machine Learning》(Coursera 新版)
  - 周志华《机器学习》(西瓜书)选读
  - scikit-learn 官方 tutorial

**产出**:用 scikit-learn 完成一个 Kaggle Titanic 或房价预测,提交到 Kaggle。

---

## 阶段 2:深度学习基础(4 周)

**目标**:掌握神经网络与主流框架。

- 神经网络:前馈网络、反向传播、激活函数、损失函数、优化器(SGD / Adam)
- 正则化:Dropout、BatchNorm、数据增强
- CNN:卷积、池化、经典网络(LeNet、ResNet)
- RNN / LSTM / GRU:序列建模基础
- 框架:PyTorch(主)+ 简单了解 TensorFlow
- 推荐资源
  - 吴恩达《Deep Learning Specialization》
  - 李沐《动手学深度学习》(d2l.ai)
  - PyTorch 官方 tutorial

**产出**:用 PyTorch 在 CIFAR-10 上训练一个 ResNet,准确率 ≥ 85%。

---

## 阶段 3:Transformer 与大语言模型(4 周)

**目标**:理解现代 AI 的核心架构,会用 Hugging Face 调模型。

- Attention 机制、Self-Attention、Multi-Head Attention
- Transformer 架构(Encoder / Decoder)
- 预训练 + 微调范式:BERT、GPT、T5
- Tokenization:BPE、WordPiece、SentencePiece
- 主流开源模型:LLaMA、Qwen、DeepSeek、Mistral
- Hugging Face 生态:transformers / datasets / accelerate / peft
- 推荐资源
  - 论文《Attention Is All You Need》
  - The Illustrated Transformer(Jay Alammar)
  - Hugging Face NLP Course

**产出**:用 LoRA 微调一个 7B 开源模型完成特定任务(如文本分类、情感分析或风格化对话)。

---

## 阶段 4:AI 应用开发(3 周)

**目标**:把模型变成真实可用的产品。

- LLM 调用:OpenAI / Anthropic / 国产 API
- Prompt Engineering:Few-shot、CoT、ReAct
- RAG(检索增强生成):向量数据库(FAISS / Chroma / Milvus)、Embedding 模型
- Agent 框架:LangChain、LlamaIndex、Claude Agent SDK
- 工程化:FastAPI 部署、Docker、流式输出、缓存

**产出**:做一个基于 RAG 的个人知识库问答机器人,前后端可访问。

---

## 阶段 5:进阶方向(任选其一,4 周+)

按兴趣选一个方向深挖:

- **多模态**:CLIP、BLIP、Stable Diffusion、Sora 类视频生成
- **强化学习 / RLHF**:PPO、DPO、对齐技术
- **模型训练与优化**:分布式训练(DeepSpeed / FSDP)、量化、推理加速(vLLM / SGLang)
- **AI Agent**:多 Agent 协作、工具调用、长程任务规划
- **垂直领域**:AI for Science、Code、医疗、金融

---

## 学习方法建议

1. **以项目驱动学习**:每个阶段结束都要有一个能放进 GitHub 的产出
2. **读论文**:从 Transformer、BERT、GPT、LLaMA 开始,每周精读 1 篇
3. **关注前沿**:Hugging Face Daily Papers、arXiv 的 cs.CL / cs.LG、Twitter/X 上的研究者
4. **动手优先**:先跑通别人的代码,再改,再自己写
5. **建立作品集**:GitHub 持续更新,每个项目写清楚 README

---

## 推荐资源汇总

- 课程:吴恩达系列、李沐《动手学深度学习》、CS224N、CS231N
- 书籍:《深度学习》(花书)、《机器学习》(西瓜书)、《动手学深度学习》
- 社区:Hugging Face、Kaggle、Papers with Code、知乎 AI 板块
- 算力:Google Colab(免费)、Kaggle Notebook、AutoDL(国内便宜)

---

_最后更新:2026-05-28_
